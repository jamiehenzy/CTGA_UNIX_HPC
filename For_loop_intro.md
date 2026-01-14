
  <h1>For Loop Tutorial</h1>

  <p><strong>Learning goals:</strong> Use <code>for</code> loops to process multiple files, extract base names using <code>basename</code> and shell parameter expansion, and simulate file-based workflows.</p>

  <h2>Setup</h2>
  <pre><code>mkdir -p ~/unix_tutorial/seq_data
cd ~/unix_tutorial/seq_data
touch SRR00{1..6}.fastq</code></pre>

  <h2>Part 1: Basic For Loop</h2>
  Examine these lines of code and think about what they will do:
  <pre><code>for file in *.fastq; do
  echo "Processing $file"
done</code></pre>

Now open nano and add as the first line:

  <pre><code>#!/bin/bash</code></pre>

Then add the lines of code in Part 1 and give the file a title with the extension for scripts, ".sh".
Make the script executable: 

 <pre><code>chmod +x yourfilename.sh</code></pre>


  <div class="feedback">
    <strong>Expected output:</strong> One line per file, like <code>Processing SRR001.fastq</code>
  </div>
What happens if you run the script from a different directory?

  <h2>Part 2: Extract base name with basename</h2>
  <pre><code>for file in *.fastq; do
  base=$(basename "$file" .fastq)
  echo "Base name: $base"
done</code></pre>

  <h2>Part 3: Extract base name with shell expansion</h2>
  <pre><code>for file in *.fastq; do
  base="${file%.fastq}"
  echo "Base name: $base"
done</code></pre>

Compare the speed of the basename and shell expansion methods by typing <code>time</code> on the command line in front of <code>bash</code>.
For example: 
<pre><code>time bash yourscript.sh</code></pre>   
or
<pre><code>time .\/yourscript.sh</code></pre>


  <h2>Part 4: Create directories per sample</h2>
  <pre><code>for file in *.fastq; do
  sample="${file%.fastq}"
  mkdir "$sample"
  echo "Created folder for $sample"
done</code></pre>

  <h2>Part 5: Simulate output file per sample</h2>
  <pre><code>for file in *.fastq; do
  sample="${file%.fastq}"
  echo "Simulated analysis of $file" > "$sample/${sample}_log.txt"
done</code></pre>

  <div class="exercise">
    <strong>Exercise 2:</strong> Check that each folder has a <code>_log.txt</code> file inside.
  </div>

  <h2>Challenge: Rename .fastq to .fq</h2>
  <pre><code>for file in *.fastq; do
  new="${file%.fastq}.fq"
  mv "$file" "$new"
done</code></pre>

  <h2>Wrap-Up Quiz</h2>
  <pre><code>for file in *.fq; do
  echo "Now working on: ${file%.fq}"
done</code></pre>

  <div class="feedback">
    <strong>Expected:</strong> For <code>SRR004.fq</code>, it should print <code>Now working on: SRR004</code>
  </div>
</body>
</html>
