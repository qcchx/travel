# RISC-V Summit North America 2023 (Santa Clara)
## Introduction
This a 3-day event from 6th to 8th Nov. The first day was the member-only event while the rest were more focus on marketing, general introduction, demo, poster and socalization. Almost all sessions were less than 30-min, so not much of deep technical ones. Since Qualcomm is the sponsor of the organziation, I was able to attend the member-only events. The session videos can be found here: https://www.youtube.com/playlist?list=PL85jopFZCnbMfMRR25ENcRkhhAUGwP5C5
## Day-1
I was late for the RISC-V 101 due to public transportation hiccups. This was a great half-day introduction sessions for RISC-V beginners. One of the sessions was about the point of entry for companies to get access to RISC-V technology:
- RISC-V exchange: a official marketplace for hardware, software, services and trainings.
- OpenHW group: open-source cores related offerings.
- RISE (RISC-V Software Ecosystem): open-source software for RISC-V
- Vendor-specific sites like Green Hills for Software, Andres as a core provider, and Microchip as a silicon provider.

The next session talked about "Buy vs Make" mindset when coming to RISC-V. As expected, there are tradeoffs to balance among flexibilty, cost and easy-of-use. There are more companies providing high quality offerings like MIPS Technologies had been switched to embrace RISC-V lately and give up on MIPS ISA. Seagate (most famous for its storage products) is getting into the customized RISC-V core business. In that sense, RISC-V does open up a new world of open markets for hardware ecosystem where a single vendor like ARM Ltd. has no match of it.

In the afternoon, I attended the Priledged Software HC (Horizontal Committee). They were pretty happy to see in the last year that IOMMU Architecute Specification and Advanced Interrupt Architecture Specification had been ratified. Then, I attended the Unprivileged Specification ISA Committee where finally meet one of the founders, Krste Asanovic in person.

Later, in Secuirty HC, One of the most projects people are working on is CHERI (Capability Hardware Enhanced RISC Instructions) which was based on the research from University of Cambridge. It has already been implemented in ARM, and the RISC-V implementation would only be conceptual compatible with ARM.

Next, in SOC Infrastructure HC, people are working on DTPM (Debug Trace and Performance Monitoring) SIG where there are two technology. One is E-trace (Efficent Trace), and the other is N-trace (Nexus-based Trace). In a nutshell, N-trace provides more complete, end-to-end trace from cores to interconnect in SOC. To trace multiple harts (cores), it needs one encoder per hart. We can also trace ony part of the system by using triggers. Then, it will send the full messages when something went wrong.

There was a wonderful socal event hosted by Impera where the whole ballroom was packed with music, drinks and food. Unfortunately, I had to leave early to catch the public transportations.
## Day-2
First, the keynote from RISC-V International CEO to look back as a sucessful year of 2023. RISC-V Lab was created to CI testing for software and host machine resources for community to develop software ecosystems. Two market development groups had also been formed this year.
