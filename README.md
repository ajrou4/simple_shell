<!DOCTYPE html>
<html>
<head>
	<title>README - Shell Implementation Project</title>
</head>
<body>
	<h1>Project Description</h1>
	<p>This project is an implementation of a basic shell, similar to the Unix shell. The shell is a command-line interface that allows users to interact with the operating system by entering commands. The shell reads user input, interprets the command, and executes it.</p>
  <p>This implementation of the shell is written in C and supports basic shell functionality such as executing commands, changing directories, and environment variables. It also supports background processes, input/output redirection, and pipeline commands.</p>

<h2>Installation</h2>
<ol>
	<li>Clone this repository to your local machine using the following command:
		<code>git clone https://github.com/&lt;ajrou4&gt;/shell-implementation.git</code></li>
	<li>Navigate to the project directory using the following command:
		<code>cd shell-implementation</code></li>
	<li>Compile the program using the following command:
		<code>make</code></li>
	<li>Run the shell using the following command:
		<code>./shell</code></li>
</ol>

<h2>Usage</h2>
<p>Once you have started the shell, you can enter commands in the following format:</p>
<code>command [arguments]</code>

<p>You can also use the following special commands:</p>
<ul>
	<li><code>cd [directory]</code>: change the current working directory to the specified directory</li>
	<li><code>exit</code>: exit the shell</li>
</ul>

<p>You can also use the following features:</p>
<ul>
	<li><code>&amp;</code>: run a command in the background</li>
	<li><code>&gt;</code>: redirect output to a file</li>
	<li><code>&lt;</code>: redirect input from a file</li>
	<li><code>|</code>: pipe the output of one command as input to another command</li>
</ul>

<h2>Contributors</h2>
<p>This project was created by the ALX Africa community as part of the C code sprint.</p>
<p>Contributors include:</p>
<ul>
	<li>mohamed ajrou (@ajrou4)</li>
	<li>Amara Ukoha(@Amytechie)</li>
</ul>
</body>
</html>
