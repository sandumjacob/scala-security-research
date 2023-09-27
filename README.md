# scala-security-research

# Open Source Issues
## better-files
unzip directory traversal/zipslip
https://github.com/pathikrit/better-files/issues/624
Fixed: https://github.com/pathikrit/better-files/pull/633

### Affected
[https://github.com/search?q=.unzipTo&type=code
](https://github.com/search?q=.unzipTo+language%3Ascala&type=code)
[https://cromwell.readthedocs.io/en/stable/search.html?q=zip
](https://github.com/broadinstitute/cromwell)
[https://github.com/joernio/joern/blob/4c1cfb1e0857ee2756f60fc1d93ff885335d9b01/joern-cli/frontends/jimple2cpg/src/main/scala/io/joern/jimple2cpg/util/ProgramHandlingUtil.scala#L91
](https://github.com/joernio/joern)

# Code Review List
## scala.io
https://www.scala-lang.org/api/2.13.6/scala/io/Source$.html
fromFile directory traversal

# Tooling
https://github.com/sandumjacob/zipslip-clusterbomb

https://joern.io/
