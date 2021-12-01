---
layout: page
---

# Curlgrep
**Curlgrep** (often stylized as **curlgrep** or `curl | grep`) is an act of retrieving and filtering information from an external source, such as the Internet. The term is derived as the concatenation of two common command-line utilities, [**cURL**](https://en.wikipedia.org/wiki/CURL) and [**grep**](https://en.wikipedia.org/wiki/Grep). Since many [command-line intepreters](https://en.wikipedia.org/wiki/Command-line_interface) allow the use of [pipes and redirections](https://en.wikipedia.org/wiki/Redirection_(computing)), both utilities can be used to extract certain information from plaintext documents (e.g. [HTML](https://en.wikipedia.org/wiki/HTML)) stored in [computer networks](https://en.wikipedia.org/wiki/Computer_network).

## Usage
### In computer administration
A curlgrep process may be invoked by retrieving the content by invoking the command `curl`, then using the redirection operator (`|`) to pipe the printed output of `curl` to be filtered by the `grep` command-line utility.

For example, to fetch a list of external links found on https://hackapedia.reinhart1010.id, a user may use the following command:

`curl https://hackapedia.reinhart1010.id | grep -Eo "(http|https)://[a-zA-Z0-9./?=_%:-]*"`

The `curl` utility will fetch and displays the full result of the webpage hosted at https://hackapedia.reinhart1010.id, while the `grep` utility will filter out the displayed results according to a specific regular expression rule to only select valid parts of the text containing valid [HTTP(S)](https://en.wikipedia.org/wiki/HTTPS) [URL scheme](https://en.wikipedia.org/wiki/URL).

### In [rootprints](rootprints.html)
Many [rootheads](roothead.html) tend to use the word **curlgrep** to refer to the retrieval and filtering process of an external content, while the term **catgrep** may be used to retrieve and filter information from an internal source (such as dotfiles). Some valid examples (in the English variant of rootprints) include:

+ *i have **curlgrepped** that there are exactly 7114 [711As](711a.html) on that website;*
+ *let's see if [eve](https://en.wikipedia.org/wiki/Alice_and_Bob) can even **curlgrep** our encrypted feelings[], alice!*
+ remember guys[], **curlgrepping** without [*ptrs[]](https://en.wikipedia.org/wiki/Pointer_(computer_programming)) means [plagiarism](https://en.wikipedia.org/wiki/Plagiarism)!