# cryptoquiztool

CryptoQuizTool.
Mac Command Line interface to the CryptoQuizKit library (for producing CryptoQuiz puzzles).

Uses swift packages swift-argument-parser & CryptoQuizKit.

CryptoQuizzes are the puzzle where some text, usually a sentence or quote, where the characters have been changed, using a simple substitution code. A key is used, or generated, where the first letter show what an A should be changed to, 2nd character shows what a B should be changed to, and so on. This encrypted puzzles can usually be puzzled out (assuming there are enough characters).

This command line tool helps a puzzle maker, or puzzle app, create these puzzles.

Revision: 1
Version: 1.0.0

To Clone: % git clone https://github.com/magesteve/cryptoquiztool

---

USAGE: cryptoquiztool [--decrypt] [--key <key>] <phrase>

ARGUMENTS:
  <phrase>                The phrase to Encrypt/decrypt. 

OPTIONS:
  --decrypt               Decrypt. 
  -k, --key <key>         Key string to use to encrypt or decrypt. This must contain 26 letters of alphabet scrambled. 
  -h, --help              Show help information.

Examples:

% cryptoquiztool "This is a Test"
% cryptoquiztool --key "BCDEFGHIJKLMNOPQRSTUVWXYZA" "Single Letter Substitution"
% cryptoquiztool --decrypt --key "BCDEFGHIJKLMNOPQRSTUVWXYZA" "XPX"
