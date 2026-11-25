# Guidance Reconciler

**Check the guidance a company gave last quarter against what it actually reported this quarter, line by line.**

Paste two texts: the guidance (last quarter's outlook or call) on the left, this quarter's earnings release on the right. Guidance Reconciler extracts every guided metric it can find, pairs each one with the reported figure on the same basis, and gives a verdict per line. Deterministic reconciliation, no AI, no account, no server.

## The five verdicts

- **Met**: the reported figure lands inside the guidance range
- **Beat**: above the top of the range, with the gap and the attainment rate against the midpoint spelled out
- **Missed**: below the bottom of the range
- **Basis check**: the metric is there, but the basis does not line up (guidance gave a percentage, the release gave a money figure, or the other way round). Flagged, never force-judged
- **Not mentioned**: the guidance had it, the release does not. The line a company quietly stops reporting shows up here

Every verdict sits next to the two original sentences, so you can check the checker.

## Also in the file

- New guidance for next quarter, found inside this quarter's release, is extracted into an archive list. Next quarter, that list is your left column
- Numbers in the guidance that match no known metric are listed as unclassified, not silently dropped
- Works on English releases, and on Chinese-language ones too (the metric dictionary is bilingual)
- A copyable plain-text summary of the whole reconciliation

## Use it

- **In the browser, nothing to install:** open the tool page at miaobuilds.com/guidance-reconciler/
- **As a file:** download `guidance-reconciler-en.html` from the v1 release and open it in any browser

One file. It runs entirely on your machine, makes no network calls, and uploads nothing. Your unpublished notes never leave your computer.

## The demo

The built-in demo is a fictional company, NorthPeak, with one of each verdict buried in it: a revenue beat, a gross margin miss, an operating-expenses basis mismatch, a capex line that vanishes, and a Data Center beat. Load it and see all five.

## Origin

Tool No.002 from [MiaoBuilds](https://miaobuilds.com). English edition of the KaiWuSuo guidance reconciler, built in public, one tool at a time.

## License

MIT for this free version.
