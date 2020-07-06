# cryptoquiztool

CryptoQuizTool.
Mac Command Line interface to the CryptoQuizKit library (for producing CryptoQuiz puzzles).

Uses swift packages swift-argument-parser & CryptoQuizKit.

USAGE: cryptoquiztool [--decrypt] [--key <key>] <phrase>

ARGUMENTS:
  <phrase>                The phrase to Encrypt/decrypt. 

OPTIONS:
  --decrypt               Decrypt. 
  -k, --key <key>         Key string to use to encrypt or decrypt. This must contain 26 letters of alphabet scrambled. 
  -h, --help              Show help information.

