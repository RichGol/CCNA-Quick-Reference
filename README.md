# The CCNA Quick Reference Guide

<p align="center">
  <img src="https://github.com/RichGol/CCNA-Quick-Reference/blob/main/images/CCNA_RefDoc.gif?raw=true" alt="CCNA_RefDoc.gif" width="60%"/>
</p>

## Purpose

This GitHub repository hosts a personal project to organize CCNA 200-301 material and IEEE 802 protocols for quick reference and study. It is not a replacement for official CCNA learning material and does not include all topics covered by the current CCNA 200-301 exam.

The project is written in the LaTeX markup language, which typesets a searchable PDF document. This repository primarily exists to share the document with those who find it useful, although those who are curious are welcome to explore the underlying LaTeX code.

*Note: The LaTeX code most likely does NOT adhere to best-practices, as I am self-taught and solve issues as they arise. This is not my first LaTeX document, and it will not be my last.*

I created this project shortly after becoming CCNA certified in order to more legibly organize my personal study notes. I am sharing it in the hope of helping others who are pursuing their own interests in networking.

## Document Features

- Fully searchable PDF written and compiled in LaTeX, allowing for internal links to each topic section/subsection. Topics are organized according to the TCP/IP Network Model (Layer 1 through Layer 5), plus QoS, MPLS, and Appendix sections.

- Applicable topics include relevant RFC number(s), which serves as formatted hyperlink(s) (via [datatracker.ietf.org](https://datatracker.ietf.org/)) directly to the specified RFC(s). Note that IEEE standards are not linked at this time.

- Includes header formats for common protocols, including field names and lengths. Quick-reference tables list common field values and addresses / address blocks. The document is presented grayscale for printing compatibility.
  
  - See the [main branch](https://github.com/RichGol/CCNA-Quick-Reference/tree/main) for a color version of the document.

- Includes common network processes and features, including STP elections; OSPF DR/BDR elections; AP modes; modified EUI-64 address generation and more.

- Includes Cisco IOS configuration examples for CCNA-relevant IOS features.

- The project is fully open-source and comes with a GPL-3.0 license, allowing for modification and redistribution by others. All LaTeX code is published within this repository for easy review.

## File Structure

`CCNA_RefDoc.pdf`: The primary file, a searchable PDF that those pursuing CCNA certification or networking may find useful.

`CCNA_RefDoc.tex`: The LaTeX markup language "source code", which can be typeset by a TeX editor to create a searchable PDF.

`images`: A folder containing all images used by the project.

## Disclaimers

*This supplementary document is designed for CCNA-certified professionals and those seeking their CCNA certification. It is NOT a replacement for official computer network and/or Cisco training.* <b>DO NOT</b> *execute Cisco IOS commands within a production network, or on devices which you do not own, without express permission and full understanding of each command's impact to the system/network.*
