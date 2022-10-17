# filespliterandjoiner
File Splitter and Joiner Python

Cara penggunaan: 
fileSplitter.py [-h] [-f File Path] [-c Chunk Size | -n n_parts] MODE

<p>argument MODE:</p>
  <p>MODE           <b>split</b> or <b>join</b></p>

<p>argument tambahan:</p>
  <p>-h, --help     Bantuan</p>
  <p>-f <b>File Path</b>   Direktory file yang akan di split</p>
  <p>-c <b>Chunk Size</b>  Ukuran size split.</p>
  <p>-n <b>n_parts</b>     Jumlah bagian file yang akan di split</p>
  <p> </p>
 
  <p>Ex.:python fileSplitter.py split \path\to\file -n 10       Men Split file menjadi 10 bagian dan direktory foldernya \[filename]_SPLITTED</p>
