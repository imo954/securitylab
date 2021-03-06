# GitHub Security Lab

This is the main git repository of [GitHub Security Lab](https://securitylab.github.com/).
We use it for these main purposes:

* We use [issues on this repo](https://github.com/github/securitylab/issues?q=is%3Aissue+is%3Aopen+label%3A%22All+For+One%22) to track CodeQL [bounty requests](https://securitylab.github.com/bounties).
* We use it for publishing some of our proof-of-concept exploits (after the vulnerability has been fixed). These PoCs can be found in the [SecurityExploits](SecurityExploits) sub-directory.
* Examples of CodeQL queries, which can be found in the [CodeQL_Queries](CodeQL_Queries) sub-directory.

## CodeQL Resources

### Official resources

* [CodeQL documentation](https://codeql.github.com/docs/)
* [CodeQL GitHub repo](https://github.com/github/codeql)

### Example queries

* Java
  * [Apache Struts CVE-2018-11776](CodeQL_Queries/java/Apache_Struts_CVE-2018-11776)
* C/C++
  * [Apple XNU icmp_error CVE-2018-4407](CodeQL_Queries/cpp/XNU_icmp_error_CVE-2018-4407)
  * [Facebook Fizz integer overflow vulnerability (CVE-2019-3560)](CodeQL_Queries/cpp/Facebook_Fizz_CVE-2019-3560)
  * [Eating error codes in libssh2](CodeQL_Queries/cpp/libssh2_eating_error_codes)
* Javascript
  * [Etherpad CVE-2018-6835](CodeQL_Queries/javascript/Etherpad_CVE-2018-6835)
* C#
  * [C# Zip Slip demo](CodeQL_Queries/csharp/ZipSlip)
* GitHub Actions:
  * [pull_request_target with explicit pull request checkout](CodeQL_Queries/actions/pull_request_target.ql)
  * [Command injection from user-controlled Actions context](CodeQL_Queries/actions/script_injections.ql)

### Videos

* Conference talks/workshops:
  * [Finding security vulnerabilities in JavaScript with CodeQL - GitHub Satellite 2020](https://www.youtube.com/watch?v=pYzfGaLTqC0)
  * [Finding security vulnerabilities in Java with CodeQL - GitHub Satellite 2020](https://www.youtube.com/watch?v=nvCd0Ee4FgE)
  * [CodeQL as an auditing oracle - POC 2020](https://www.youtube.com/watch?v=XmAEgl8bVhg)
  * [mbuf-oflow: Finding Vulnerabilities In iOS/MacOS Networking Code](https://www.youtube.com/watch?v=0EHP2gzwVAY)
* CodeQL demos from the Semmle days (short Youtube videos):
  * [PII data leaks: Identifying personal information in logs with CodeQL](https://www.youtube.com/watch?v=hHaOxbyqy44)
  * [Vulnerability Hunting: Quest for an Exploit using QL](https://www.youtube.com/watch?v=irrYp3wdtsw)
  * [Finding Insecure Deserialization in Java](https://www.youtube.com/watch?v=XsUcSd75K00)
  * [Finding integer overflows in Libssh2](https://www.youtube.com/watch?v=czXicfULOfk)

### Tools

* Editor plugins
  * [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-codeql) (Official)
  * [Neovim](https://github.com/pwntester/codeql.nvim)
