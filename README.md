# InfiltratorOS Boot Manager

InfiltratorOS Boot Manager is a fork of **rEFInd**.

This project deliberately begins with the existing rEFInd codebase rather than pretending to be a clean-room or independently originated boot manager. rEFInd provides the initial working foundation while InfiltratorOS Boot Manager is progressively redesigned and rewritten for the requirements of InfiltratorOS.

## Project origin

The initial InfiltratorOS Boot Manager source tree was imported from the current rEFInd upstream `master` tree at commit:

`cf542da4459ff18535b0ae3a7910af032834e469`

That upstream commit was authored by Rod Smith on 7 January 2026.

The original rEFInd project, its authors, contributors, history, documentation, and licensing remain credited. The imported upstream documentation is retained in `README.txt`, `CREDITS.txt`, `LICENSE.txt`, `COPYING.txt`, and the other upstream files in this repository.

## Direction

The intention is not simply to rebrand rEFInd. The rEFInd codebase is the starting point.

Development will progressively replace, restructure, and rewrite the boot manager for InfiltratorOS. During that process, portions of the repository will continue to contain original or modified rEFInd code until they are replaced. Attribution and applicable licence requirements remain in force for code derived from rEFInd and its own upstream sources.

As the rewrite progresses, this repository should make the distinction clear between inherited rEFInd code and new InfiltratorOS-specific work.

## Licensing

This repository currently contains code inherited from rEFInd and rEFIt under multiple licences. rEFInd's `LICENSE.txt` states that modifications made in the rEFInd fork are covered by GNU GPL version 3, while original rEFIt portions use the rEFIt licence and some filesystem-driver components have their own GPL licensing. rEFInd documentation is covered by GNU FDL 1.3.

See `LICENSE.txt`, `COPYING.txt`, and the licence files within the relevant subdirectories for the authoritative terms.

## Upstream

rEFInd is maintained by Rod Smith. The upstream project remains the source and historical origin of the code from which InfiltratorOS Boot Manager began.
