<h1>MiniLang Scanner</h1>

<h2>Overview</h2>

<p>This project provides a simple scanner for the "MiniLang" programming language. The scanner is implemented in Python and aims to tokenize source code based on the language specifications.</p>

<h2>Scanner Code</h2>

<p>The scanner is encapsulated in the <code>MiniLangScanner</code> class, which takes a file path as an argument during initialization. The <code>scan</code> method processes the source code, and the identified tokens are stored in the <code>tokens</code> attribute.</p>

<h3>Usage</h3>

<p>To run the scanner, execute the following command in the terminal:</p>

<pre>
<code>python minilang_scanner.py &lt;file_path&gt;</code>
</pre>

<p>Replace <code>&lt;file_path&gt;</code> with the path to the MiniLang source code file.</p>

<h3>Example</h3>

<pre>
<code>python minilang_scanner.py test1</code>
</pre>

<h2>Token Classification</h2>

<p>The scanner classifies tokens into various types, including keywords, literals, identifiers, operators, and parentheses. The classification is based on regular expressions and predefined keywords.</p>

<h3>Token Types:</h3>

<ul>
  <li><strong>KEYWORD:</strong> if, else, print</li>
  <li><strong>INTEGER_LITERAL:</strong> Numeric values</li>
  <li><strong>BOOLEAN_LITERAL:</strong> true or false</li>
  <li><strong>IDENTIFIER:</strong> Variable names</li>
  <li><strong>OPERATOR:</strong> +, -, *, /, =, ==, !=</li>
  <li><strong>PARENTHESIS:</strong> (, )</li>
</ul>

<h2>Error Handling</h2>

<p>The scanner reports lexical errors for unrecognized tokens. If an unrecognized token is encountered, an error message is printed, indicating the line number and the problematic token.</p>

<h2>Test Files</h2>

<p>Included in this repository are four test files: <code>test1</code>, <code>test2</code>, <code>test3</code>, and <code>test4</code>. Each is designed to assess different aspects of the MiniLang scanner. Follow the provided instructions to run the scanner on each test file.</p>

<p>Replace <code>testX</code> with the appropriate test file name. Each test file is carefully crafted to evaluate the scanner's ability to tokenize MiniLang source code, including various language features and potential edge cases.</p>
