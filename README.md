# Splicecress 1.0 TEST
Native Android longest-common-subsequence puzzle. Android 8+ min26/target35. Package com.gg007.splicecress.

## Rules
Known longest-common-subsequence adaptation. Two fixed eight-letter rows use A-D. Tap any letter tile to keep or remove it; each KEPT line shows selected letters in their original left-to-right order. Make both KEPT strings identical at the printed maximum target length, then press CHECK SEQUENCE. Gaps are allowed; letters need not be contiguous. Never rearrange letters. Twelve original pairs each have one longest string of length 4-6. Repeated-letter positions may give several valid embeddings, all accepted. Undo/reset, GG007 menu/site/privacy and saved palette/optional position labels. Tap the title or Android Back for menu.

## Download and status
https://mega.co.nz/#!NB1USJYB!eYLC2EcvW7HmlWweajSr2XmIzW4CTipF6eLEwKBrINY
APK 16878 bytes; SHA256 ef61e95261c4b5137fe79e44d50ac468d4ae3b731f05a912e676aae51ca94d77. Original certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions, original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 1051111 generates twelve distinct pairs of eight-letter strings. All 65536 two-row selection masks per pair, 786432 total, compare independent extracted subsequences and exhaustive-set-intersection maxima with production prefix dynamic programming and goal checks. Another 12000 toggle/undo transitions verify restoration; 1000 random pairs compare exhaustive subsequence sets against DP. Empty, single-character, gapped, nonmatching, invalid mask/tile bounds and reset cases pass. All twelve actual drawing-adapter tile/CHECK longest-sequence tap-solves, empty/full-row rejection, solved locks, actual NEXT, undo/reset/levels/title-menu/privacy/saved palette-position-labels pass. Twenty drawing previews inspected, not phone screenshots. Phone runtime, performance, browser handoff QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 236 prior studio descriptions and 803 legacy one-line descriptions reviewed. A longest-common-subsequence/string-alignment/deletion scan found no matching mechanic. Splicecress maximizes the length of an equal order-preserving string selected from two fixed rows. Covercress minimizes bundle cost for full-symbol union coverage; Rankcress reconstructs a permutation from smaller-to-right counts; Cyclecress fills a ring so all directed pairs occur once. None implements paired subsequence selection and prefix DP. Known LCS, not globally new. Original seeded string pairs, native implementation and letter-selection illustration. Six academic/textbook/tutorial sources used for definition and order/gap distinction. No source code copied or scientific claims about DNA made.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/splice-test src/com/gg007/splicecress/Board.java BoardTest.java then java -cp /tmp/splice-test com.gg007.splicecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with SpliceAdapterTest.java, not an Android runtime.

## Privacy and branding
Splicecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, position labels and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon and studio https://ilanis-agent.github.io/gg-007-gaming/.

## Preservation and publishing
Complete source/APK, exact cumulative 237-card studio and publishing fragments privately preserved:
https://files.instinct.com/vekx5wgfduxn-splicecress-source-archive
https://github.com/iLanis-agent/splicecress holds README only, full Git source pending. All four existing studio includes and prior card bytes unchanged. Pages settings untouched. Both live sites verified separately.

## Rule sources
https://www.programiz.com/dsa/longest-common-subsequence
https://www.cs.cmu.edu/~15451-s19/lectures/lec08-dp1.pdf
https://ics.uci.edu/~goodrich/teach/cs161/notes/dynamic
https://web.mit.edu/6.047/book-2012/Lecture02_DynamicProgramming/Lecture02_DynamicProgramming_standalone.pdf
https://www.cs.jhu.edu/~mdinitz/classes/IntroAlgorithms/Fall2021/Lectures/Lecture12/lecture12.pdf
https://courses.cs.washington.edu/courses/cse421/25sp/sections/section6/section06.pdf
