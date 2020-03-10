# [C++ links](README.md): Testing

See also:

- [Compilers Correctness](https://github.com/MattPD/cpplinks/blob/master/compilers.correctness.md): [testing](https://github.com/MattPD/cpplinks/blob/master/compilers.correctness.md#testing)

# Contents

- [General](#general)
- [Blogs](#blogs):
	- [Blogs - Series](#blogs-series)
- [Books](#books)
- [Courses](#courses)
- [Research](#research)
- [Concurrency](#concurrency)
- [Continuous Integration](#continuous-integration)
- [Coverage](#coverage)
- [Reduction](#reduction)
- [Software](#software):
	- [Software - Test Doubles](#software-test-doubles)
- [Talks](#talks): [2019](#talks-2019), [2018](#talks-2018), [2017](#talks-2017), [2016](#talks-2016), [2015](#talks-2015), [2014](#talks-2014)

---

# General

- [ACM Special Interest Group on Software Engineering (SIGSOFT)](https://www.sigsoft.org/)
	- Open Table of Contents (TOC) Resources - https://www.sigsoft.org/resources/opentoc.html
- Testing Standards Working Party
	- http://www.testingstandards.co.uk/
	- Living Glossary of Testing Terms - http://www.testingstandards.co.uk/living_glossary.htm
- cpp-testing-no-excuses
	- https://github.com/d-led/cpp-testing-no-excuses
- What Is a Good Test Case?
	- 2003; Cem Kaner
	- http://www.kaner.com/pdfs/GoodTest.pdf

---

# Blogs

- Google Testing Blog
	- https://testing.googleblog.com/
- Evolving Understanding About Exploratory Testing
	- https://www.developsense.com/blog/2008/09/evolving-understanding-about/
- Exploratory Testing
	- https://www.satisfice.com/exploratory-testing
- How SQLite Is Tested
	- https://sqlite.org/testing.html
- How the GNU coreutils are tested
	- http://www.pixelbeat.org/docs/coreutils-testing.html
- Principles of Automated Testing
	- http://www.lihaoyi.com/post/PrinciplesofAutomatedTesting.html
- Testing in Production, the safe way
	- https://medium.com/@copyconstruct/testing-in-production-the-safe-way-18ca102d0ef1

## Blogs - Series

- John Regehr
	- Software Testing Using Function/Inverse Pairs
		- https://blog.regehr.org/archives/708
- Kent Beck
	- Programmer Test Principles
		- https://medium.com/@kentbeck_7670/programmer-test-principles-d01c064d7934
	- “Unit” Tests? 
		- https://www.facebook.com/notes/kent-beck/unit-tests/1726369154062608/
- Nelson Elhage
	- Two kinds of testing - https://blog.nelhage.com/post/two-kinds-of-testing/
	- How I Write Tests - https://blog.nelhage.com/2016/12/how-i-test/
	- Design for Testability - https://blog.nelhage.com/2016/03/design-for-testability/
- William Caputo
	- TDD: "Failing to Falsify"
		- http://logosity.net/notes.html#2017.02
	- The goal of "unit testing" in TDD
		- http://logosity.net/notes.html#2017.09

---

# Books

- Software Testing: From Theory to Practice
	- Maurício Aniche & Arie van Deursen
	- https://sttp.site/
- The Fuzzing Book: Tools and Techniques for Generating Software Tests
	- Andreas Zeller, Rahul Gopinath, Marcel Böhme, Gordon Fraser, Christian Holler
	- https://www.fuzzingbook.org/

---

# Courses

- CMPT 473: Software Testing, Reliability and Security
	- http://www2.cs.sfu.ca/~wsumner/teaching/473/
- Software Analysis and Testing
	- [Mayur Naik](http://www.cis.upenn.edu/~mhnaik/)
	- https://RightingCode.org/
	- http://www.cis.upenn.edu/~mhnaik/edu/cis700/
	- https://www.youtube.com/channel/UCvwqRhlkE_Wm2FF9qzvHfJw
- Software Testing: How to Make Software Fail
	- John Regehr & Sean Bennett
	- https://www.udacity.com/course/software-testing--cs258

---

# Research

## Readings - Research - 2010s

- Assertions Are Strongly Correlated with Test Suite Effectiveness
	- ESEC/FSE 2015
	- Yucheng Zhang, Ali Mesbah 
	- http://salt.ece.ubc.ca/publications/fse15.html
- Assurances in Software Testing: A Roadmap
	- ICSE-NIER 2019: International Conference on Software Engineering: New Ideas and Emerging Results
	- Marcel Böhme
	- https://arxiv.org/abs/1807.10255
- AUSTIN (AUgmented Search-based TestINg): An open source tool for search based software testing of C programs
	- Search Based Software Engineering (SSBSE) 2010; Information and Software Technology, 55(1), 2013
	- Kiran Lakhotia, Mark Harman, Hamilton Gross
	- http://www0.cs.ucl.ac.uk/staff/K.Lakhotia/docs/ist12.pdf
	- http://www0.cs.ucl.ac.uk/staff/mharman/ist-kiran.pdf
	- http://www0.cs.ucl.ac.uk/staff/Yuanyuan.Zhang/StuConOS/StuConOS-Kiran.pdf
	- https://code.google.com/archive/p/austin-sbst/
	- https://github.com/kiranlak/austin-sbst
- Compiler Instrumentation for Testing
	- https://github.com/martong/finstrument_mock
	- Unit Testing in C++ with Compiler Instrumentation and Friends
		- Acta Cybernetica 23 (2017)
		- Gábor Márton and Zoltán Porkoláb
		- http://www.inf.u-szeged.hu/actacybernetica/edb/vol23n2/actacyb_23_2_2017_14.xml
		- http://www.inf.u-szeged.hu/actacybernetica/edb/vol23n2/pdf/actacyb_23_2_2017_14.pdf
	- Compile-Time Function Call Interception for Testing in C/C++
		- Studia Universitatis Babeș-Bolyai Informatica, v. 63, n. 1, 2018
		- Gábor Márton, Zoltán Porkoláb
		- http://www.cs.ubbcluj.ro/~studia-i/journal/journal/article/view/19
		- https://www.researchgate.net/publication/325900400_Compile-Time_Function_Call_Interception_for_Testing_in_CC
- Does Refactoring of Test Smells Induce Fixing Flaky Tests?
	- International Conference on Software Maintenance and Evolution (ICSME) 2017
	- Fabio Palomba and Andy Zaidman
	- https://azaidman.github.io/publications/palombaICSME2017.pdf
	- https://www.slideshare.net/fabiopalomba/does-refactoring-of-test-smells-induce-fixing-flaky-tests
- Regression Testing Minimisation, Selection and Prioritisation: A Survey
	- Software Testing, Verification and Reliability 22, 2 (2012)
	- Shin Yoo and Mark Harman
	- http://www0.cs.ucl.ac.uk/staff/M.Harman/stvr-shin-survey.pdf
- STADS: Software Testing as Species Discovery
	- ACM Trans. Softw. Eng. Methodol. 27(2) 2018
	- Marcel Böhme
	- https://dl.acm.org/citation.cfm?doid=3210309
	- https://arxiv.org/abs/1803.02130
- Testing C++ generic libraries
	- International Conference on Software Maintenance (ICSM) 2012
	- Andrew Sutton, Marcin Zalewski
	- https://ieeexplore.ieee.org/document/6405251
	- https://www.ii.uib.no/~magne/inf328s17-info/inf328-2017s-bldl-presentation-08-SuttonZalewski2012icsm-06405251.pdf
- The Art of Testing Less Without Sacrificing Quality
	- ICSE 2015
	- Kim Herzig, Michaela Greiler, Jacek Czerwonka, Brendan Murphy
	- https://www.microsoft.com/en-us/research/publication/the-art-of-testing-less-without-sacrificing-quality/
	- https://blog.acolyer.org/2015/06/25/the-art-of-testing-less-without-sacrificing-quality/
- The Oracle Problem in Software Testing: A Survey
	- IEEE Transactions on Software Engineering 41(5) 2015
	- Earl Barr, Mark Harman, Phil McMinn, Muzammil Shahbaz, Shin Yoo
	- https://ieeexplore.ieee.org/document/6963470
	- http://earlbarr.com/publications/testoracles.pdf
	- Repository of Publications on the Test Oracle Problem
		- http://crestweb.cs.ucl.ac.uk/resources/oracle_repository/
- Tools and Language Elements for Testing, Encapsulation and Controlling Abstraction in Large Scale C++ Projects
	- 2019 Doctoral dissertation; Gábor Márton
	- http://www.tnkcs.inf.elte.hu/vedes/Marton_Gabor_Ertekezes1.pdf
	- https://www.researchgate.net/publication/337717375_Tools_and_Language_Elements_for_Testing_Encapsulation_and_Controlling_Abstraction_in_Large_Scale_C_Projects
- When Testing Meets Code Review: Why and How Developers Review Tests
	- ICSE 2018
	- Davide Spadini, Mauricio Aniche, Margaret-Anne Storey, Magiel Bruntink, Alberto Bacchelli
	- https://pure.tudelft.nl/portal/en/publications/when-testing-meets-code-review-why-and-how-developers-review-tests(256e7d56-352f-44ae-919b-97fad0eafe69).html
	- https://pure.tudelft.nl/portal/files/38853938/PID5219697.pdf

## Readings - Research - 2000s

- Software Testing and Industry Needs
	- IEEE Software, vol. 23, no. 4, July-Aug. 2006
	- R. L. Glass, R. Collard, A. Bertolino, J. Bach, C. Kaner
	- https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=1657939
	- https://ieeexplore.ieee.org/document/1657939/
- Software Testing Research: Achievements, Challenges, Dreams
	- Future of Software Engineering 2007; Antonia Bertolino
	- http://selab.netlab.uky.edu/homepage/sw-test-roadmap-bertolino.pdf

## Readings - Research - 1990s

- Bringing Testing Into the Fold
	- IEEE Software 13(3): 91-92 (1996)
	- Edward V. Berard
	- https://doi.org/10.1109/52.493025
- PIE: A Dynamic Failure-Based Technique
	- Jeffrey M. Voas
	- IEEE Transactions on Software Engineering, Volume 18 Issue 8, 1992
	- https://dl.acm.org/citation.cfm?id=136558
	- http://www.cs.odu.edu/~mln/ltrs-pdfs/NASA-92-ieeeswe.jmv.pdf
	- PIE: propagation, infection, and execution

## Readings - Research - 1980s

- On Testing Non-Testable Programs
	- The Computer Journal, vol. 25, no. 4, 1982
	- E. J. Weyuker
	- https://academic.oup.com/comjnl/article/25/4/465/366384

---

# Concurrency

- A Survey of Recent Trends in Testing Concurrent Software Systems
	- IEEE Transactions on Software Engineering (TSE), vol. 44, no. 8, 2018
	- https://www.computer.org/csdl/trans/ts/2018/08/07932530-abs.html
	- https://home.deib.polimi.it/margara/papers/2017_tse_testing_concurrent_software.pdf
- Applications of synchronization coverage
	- Principles and practice of parallel programming (PPoPP) 2005
	- Arkady Bron, Eitan Farchi, Yonit Magid, Yarden Nir, and Shmuel Ur
	- https://doi.org/10.1145/1065944.1065972 
- Are Concurrency Coverage Metrics Effective for Testing: A Comprehensive Empirical Investigation
	- Journal of Software Testing, Verification and Reliability (STVR) 25(4) 2015
	- S. Hong, M. Staats, J. Ahn, M. Kim, G. Rothermel
	- http://onlinelibrary.wiley.com/doi/10.1002/stvr.1539/abstract
	- https://orbilu.uni.lu/bitstream/10993/16540/1/main-journal-concurrent-cov-effectiveness.pdf

---

# Continuous Integration

- ci_helloworld: A simple example of how to setup a complete CI environment for C and C++
	- https://github.com/ainfosec/ci_helloworld
	- A Test a Day Keeps Your Manager Away!
		- CppCon 2017; Rian Quinn
		- https://www.youtube.com/watch?v=KdJhQuycD78
		- "During this session we will step through an open source project designed to demonstrate how to integrate different C++ analysis tools into your CI services. These tools include static analysis (Clang Tidy, Coverity Scan, Codeacy and CppCheck), dynamic analysis (Valgrind and Google's Sanitizers), source formatting (Astyle and Clang Format), documentation (Doxygen), code coverage (Codecov, Coveralls, and LLVM's Software-based Code Coverage), cross platform tests (Windows, Cygwin, Linux, and macOS), compiler tests (GCC, Clang, and Visual Studio) and finally C++ libraries designed to assist in reliability and automated testing (Catch, Hippomocks and the Guideline Support Library). In addition we will openly discuss the advantages and disadvantages of using various analysis tools, how to integrate these tools into existing projects (both large and small) as well as common problems encountered while using these tools autonomously in a CI environment."
- Code Coverage & Continuous Integration
	- 2019 ATPESC Tutorial: Better Scientific Software
	- Jared O'Neal
	- https://www.youtube.com/watch?v=8JZi7OvGGCc
	- https://doi.org/10.6084/m9.figshare.9272813
	- Examples
		- Travis CI Hello World: Simplest CI example
			- https://github.com/jrdoneal/CI_HelloWorld
			- https://travis-ci.org/jrdoneal/CI_HelloWorld
		- CI_Multiplatform: Multiplatform/Multicompiler Travis CI Example
			- CI example w/ multiple platforms and specific compiler versions
			- https://github.com/jrdoneal/CI_Multiplatform
		- Code coverage, testing, and CI example (Fortran, C++)
			- https://github.com/jrdoneal/infrastructure

## Continuous Integration - Readings

- Automated Reporting of Anti-Patterns and Decay in Continuous Integration
	- ICSE 2019
	- Carmine Vassallo, Sebastian Proksch, Harald Gall, Massimiliano Di Penta
	- http://doi.org/10.5281/zenodo.2578271
- Continuous delivery: Patterns and antipatterns in the software life cycle
	- DZone refcard #145, 2011; P. M. Duvall
	- https://dzone.com/refcardz/continuous-delivery-patterns.
- Continuous Integration: Improving Software Quality and Reducing Risk
	- 2007; P. Duvall, S. M. Matyas, A. Glover
	- http://www.integratebutton.com/
- Continuous Integration Theater
	- Empirical Software Engineering and Measurement (ESEM) 2019
	- Wagner Felidré, Leonardo Furtado, Daniel da Costa, Bruno Cartaxo, Gustavo Pinto
	- https://arxiv.org/abs/1907.01602
	- http://gustavopinto.org/blog/continuous-integration-theater/
- Game Changers - Trunk Based Development
	- https://trunkbaseddevelopment.com/game-changers/
- How to get code coverage from CI
	- https://codingnest.com/how-to-get-code-coverage-from-ci/
- Modern C++ CI
	- CMake, Catch, spdlog, Travis, AppVeyor
	- https://juan-medina.com/2017/07/01/moderncppci/
	- https://github.com/LearningByExample/ModernCppCI
- Taming Google-Scale Continuous Testing
	- ICSE 2017
	- Atif Memon, Bao Nguyen, Eric Nickell, John Micco, Sanjeev Dhanda, Rob Siemborski, Zebao Gao
	- https://research.google/pubs/pub45861/

## Continuous Integration - Software

- Azure DevOps C++ build tasks for CMake and vcpkg
	- https://github.com/lukka/CppBuildTasks
- CMake Modern: C++, CMake and Travis-CI Hello World
	- https://github.com/nboutin/cmake_modern
- Continuous Integration Demo
	- A demo project for C++14 using CI systems like Travis CI, Circle CI, Google Test, Catch, etc.
	- https://github.com/daixtrose/continuous-integration-demo
- GitLab CI for C++ projects
	- https://mklimenko.github.io/english/2020/02/02/gitlab-ci-cpp/

### Continuous Integration - Software - AppVeyor

- Intro to AppVeyor - C++ Weekly - Ep 80
	- https://www.youtube.com/watch?v=R8OrWVVf5CM
- Boost.Hana .appveyor.yml
	- https://github.com/boostorg/hana/blob/master/.appveyor.yml

### Continuous Integration - Software - GitHub Actions 

- Using GitHub Actions with C++ and CMake
	- https://cristianadam.eu/20191222/using-github-actions-with-c-plus-plus-and-cmake/
- Speeding up C++ GitHub Actions using ccache
	- https://cristianadam.eu/20200113/speeding-up-c-plus-plus-github-actions-using-ccache/

### Continuous Integration - Software - Travis

- .travis.yml Examples
	- Boost.Hana: clang++, g++, Boost, Valgrind - https://github.com/boostorg/hana/blob/master/.travis.yml
	- Catch2: https://github.com/catchorg/Catch2/blob/master/.travis.yml
	- meta: https://github.com/Leandros/meta/blob/master/.travis.yml
	- MPark.Variant: https://github.com/mpark/variant/blob/master/.travis.yml
	- xstd: clang++, g++, binutils, Boost, libc++, lcov, lld, lldb - https://github.com/rhalbersma/xstd/blob/master/.travis.yml
- C++ CI: Clang, Travis, CMake, GTest, Coveralls & Appveyor
	- http://david-grs.github.io/cpp-clang-travis-cmake-gtest-coveralls-appveyor/
	- https://github.com/david-grs/clang_travis_cmake_gtest_coveralls_example
- Intro To Travis CI - C++ Weekly - Ep 79
	- https://www.youtube.com/watch?v=3ulKzD2cmSw
- Continuous integration with Travis CI
	- https://arne-mertz.de/2017/04/continuous-integration-travis-ci/
- icc-travis: Script to help install Intel C/C++ Compiler on Travis CI.
	- https://github.com/nemequ/icc-travis
- Minimal Travis CI example for modern C++
	- https://github.com/mpoullet/travis-cpp
- Richel Bilderbeek
	- C++ Travis CI tutorial
		- http://richelbilderbeek.nl/CppTravisCiTutorial.htm
		- https://github.com/richelbilderbeek/travis_cpp_tutorial
	- Favorite C++ setup
		- https://github.com/richelbilderbeek/the_richel_setup
- TravisTorrent: Synthesizing Travis CI and GitHub for Full-Stack Research on Continuous Integration
	- https://travistorrent.testroots.org/

---

# Coverage

## Coverage - Readings

- A Large-Scale, Longitudinal Study of Test Coverage Evolution
	- Automated Software Engineering (ASE) 2018
	- Michael Hilton, Jonathan Bell, Darko Marinov
	- http://jonbell.net/publications/coverage
	- https://www.code-coverage.org/publications/
	- Code Coverage Analytics: Understanding how lines are (un)covered
		- https://www.code-coverage.org/
- Applications of Synchronization Coverage
	- Principles and practice of parallel programming (PPoPP) 2005
	- Arkady Bron, Eitan Farchi, Yonit Magid, Yarden Nir, and Shmuel Ur
	- https://doi.org/10.1145/1065944.1065972 
- Assessing Oracle Quality with Checked Coverage
	- International Conference on Software Testing, Verification and Validation ICST 2011
	- David Schuler and Andreas Zeller
	- https://dl.acm.org/citation.cfm?id=1990075
- Automatic Self-Validation for Code Coverage Profilers
	- ASE 2019
	- Yibiao Yang, Yanyan Jiang, Zhiqiang Zuo, Yang Wang, Hao Sun, Hongmin Lu, Yuming Zhou, Baowen Xu
	- https://2019.ase-conferences.org/details/ase-2019-papers/2/Automatic-Self-Validation-for-Code-Coverage-Profilers
- Can Testedness be Effectively Measured
	- FSE 2016
	- Ahmed, Gopinath, Brindescu, Groce, Jensen
	- https://rahul.gopinath.org/resources/fse2016/ahmed2016can.pdf
	- https://speakerdeck.com/ahmedi/can-testedness-be-effectively-measured
	- https://rahul.gopinath.org/publications/#ahmed2016can
- Code Coverage at Google
	- ESEC/FSE 2019
	- Marko Ivanković, Goran Petrović, René Just, Gordon Fraser
	- https://homes.cs.washington.edu/~rjust/publ/google_coverage_fse_2019.pdf
	- https://ai.google/research/pubs/pub48413/
- Code Coverage for Suite Evaluation by Developers
	- ICSE 2014
	- Rahul Gopinath, Carlos Jensen, Alex Groce
	- http://research.engr.oregonstate.edu/hci/sites/research.engr.oregonstate.edu.hci/files/papers/gopinath2014code_0.pdf
- Code Coverage is a Strong Predictor of Test Suite Effectiveness
	- GTAC 2016
	- Rahul Gopinath
	- https://www.youtube.com/watch?v=NKEptA3KP08
	- https://speakerdeck.com/rahulgopinath/code-coverage-is-a-strong-predictor-of-test-suite-effectiveness-in-the-real-world
	- https://docs.google.com/presentation/d/1_bNn_HTI1Vst6WAB62KHTtgbvxocjpnt2Y-8ugGyP8U
- Comparing non-adequate test suites using coverage criteria
	- International Symposium on Software Testing and Analysis (2013)
	- Gligoric, M., Groce, A., Zhang, C., Sharma, R., Alipour, A., Marinov, D.
	- https://agroce.github.io/issta13.pdf
- Coverage and Its Discontents 
	- Onward! Essays, SPLASH 2014
	- Alex Groce, Mohammad Amin Alipour, Rahul Gopinath
	- https://agroce.github.io/onwardessays14.pdf
- Coverage is Not Strongly Correlated with Test Suite Effectiveness
	- International Conference on Software Engineering 2014
	- Laura Inozemtseva and Reid Holmes
	- http://www.linozemtseva.com/research/2014/icse/coverage/
	- ICSE 2014: https://vimeo.com/92273013
	- GTAC 2015: https://www.youtube.com/watch?v=sAfROROGujU
- Covrig: A Framework for the Analysis of Code, Test, and Coverage Evolution in Real Software
	- ISSTA 2014
	- Paul Marinescu, Petr Hosek, Cristian Cadar
	- https://srg.doc.ic.ac.uk/publications/covrig-issta-14.html
- Guidelines for coverage-based comparisons of non-adequate test suites
	- ACM Transactions on Software Engineering and Methodology (2015)
	- Gligoric, M., Groce, A., Zhang, C., Sharma, R., Alipour, A., Marinov, D.
	- https://dl.acm.org/citation.cfm?id=2660767
	- http://mir.cs.illinois.edu/coco/
	- http://users.ece.utexas.edu/~gligoric/papers/GligoricETAL15CoCoJournal.pdf
- How to Misuse Code Coverage
	- 1999; Brian Marick
	- http://www.exampler.com/testing-com/writings/coverage.pdf
- Hunting for Bugs in Code Coverage Tools via Randomized Differential Testing
	- ICSE 2019
	- Yibiao Yang, Yuming Zhou, Hao Sun, Zhendong Su, Zhiqiang Zuo, Lei Xu, Baowen Xu
	- https://2019.icse-conferences.org/event/icse-2019-technical-papers-how-reliable-are-code-coverage-tools-
- Invasive Software Testing: Mutating Target Programs to Diversify Test Exploration for High Test Coverage
	- IEEE International Conference on Software Testing, Verification and Validation (ICST) 2018
	- Y. Kim, S. Hong, B. Ko, L. Phan, M. Kim
	- http://swtv.kaist.ac.kr/publications/icst18-deminer.pdf
- Mythical Unit Test Coverage 
	- IEEE Software, Volume 35, Issue 3, May/June 2018
	- V. Antinyan, J. Derehag, A. Sandberg, M. Staron
	- https://ieeexplore.ieee.org/document/8354427/
	- https://www.researchgate.net/publication/324959836_Mythical_Unit_Test_Coverage
- Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization
	- Yanhao Wang, Xiangkun Jia, Yuwei Liu, Tiffany Bao, Dinghao Wu, and Purui Su
	- Network and Distributed System Security Symposium (NDSS) 2020
	- https://ajax4sec.github.io/papers/ndss20-fall-paper422.pdf
- Selecting Software Test Data Using Data Flow Information
	- IEEE Transactions on Software Engineering, 11(4), 1985
	- Sandra Rapps and Elaine J. Weyuker
	- http://ieeexplore.ieee.org/document/1702019/
- TestCov: Robust Test-Suite Execution and Coverage Measurement
	- ASE 2019
	- Dirk Beyer, Thomas Lemberger
	- https://2019.ase-conferences.org/details/ase-2019-Demonstrations/34/TestCov-Robust-Test-Suite-Execution-and-Coverage-Measurement
- Turning Programs against Each Other: High Coverage Fuzz-Testing using Binary-Code Mutation and Dynamic Slicing
	- ESEC/FSE 2015
	- Ulf Kargén and Nahid Shahmehri
	- https://www.ida.liu.se/~ulfka17/papers/FSE2015.pdf
- Verification, coverage and maximization: The big picture
	- https://blog.foretellix.com/2016/12/23/verification-coverage-and-maximization-the-big-picture/

## Coverage - Software

- afl-cov - AFL Fuzzing Code Coverage
	- https://github.com/mrash/afl-cov
- cmake_catch_coverage
	- Integration of CMake, Catch and CMake CodeCoverage module for C++ code. 
	- (CMake CodeCoverage depends on: gcov, gcovr, genhtml, lcov.)
	- https://github.com/fkromer/catch_cmake_coverage
- Code Coverage in Chromium
	- https://chromium.googlesource.com/chromium/src/+/master/docs/testing/code_coverage.md
- CompareCoverage
	- CompareCoverage (CmpCov in short) is a simple instrumentation module for C/C++ programs and libraries, which extracts information about data comparisons taking place in the code at run time, and saves it to disk in the form of standard .sancov files. It is based on the SanitizerCoverage instrumentation available in the clang compiler, which itself is tightly related to AddressSanitizer. Specifically, the library implements the instrumentation callbacks defined by the Tracing data flow feature of SanitizerCoverage.
	- https://github.com/googleprojectzero/CompareCoverage
- CovNavi: Code coverage navigation and analysis
	- https://github.com/Cisco-Talos/covnavi
	- Fuzzing driven code auditing and vice versa: Coverage analysis for better fuzzing
		- https://talosintelligence.com/resources/61
- cpp-llvm-coverage: How to use LLVM coverage for for C++
	- https://github.com/Longhanks/cpp-llvm-coverage
- drcov: a DynamoRIO client tool that collects code coverage information
	- Dr. Memory provides optional code coverage information to aid in fuzz testing (Fuzz Testing Mode) or in general testing.
	- http://dynamorio.org/docs/page_drcov.html
	- http://drmemory.org/docs/page_coverage.html
	- https://github.com/DynamoRIO/dynamorio/tree/master/clients/drcov
- GNU gcov
	- https://gcc.gnu.org/onlinedocs/gcc/Gcov.html
	- Writing Better Function Tests with GCOV
		- Linaro Connect 2018; Masami Hiramatsu
		- https://www.youtube.com/watch?v=U_qWLa9KnW8
	- Gcovr
		- Gcovr provides a utility for managing the use of the GNU gcov utility and generating summarized code coverage results. 
		- http://gcovr.com/
		- https://github.com/gcovr/gcovr
	- GCovHTML - Generate reports on code coverage 
		- https://gitlab.com/stone.code/gcovhtml
	- Dev Santa Claus Part 2: C++ code coverage metrics with gcov 
		- setting up code coverage metrics for a C++ codebase built using Bamboo, CMake and GCC.
		- https://genbattle.bitbucket.io/blog/2018/01/19/Dev-Santa-Claus-Part-2/
	- Using Gcov and Lcov to generate beautiful C++ code coverage statistics
		- https://codeflu.blog/2014/12/26/using-gcov-and-lcov-to-generate-beautiful-c-code-coverage-statistics/
- Kcov
	- Code coverage tool for compiled programs, Python and Bash which uses debugging information to collect and report data without special compilation options
	- http://simonkagstrom.github.io/kcov/
	- https://github.com/simonkagstrom/kcov
	- C++ Weekly - Ep 111 - kcov - https://www.youtube.com/watch?v=NRCnS5alouI
	- Kcov - gcov, lcov and bcov - https://simonkagstrom.livejournal.com/50380.html
	- Kcov - a single-step code coverage tool
		- Simon Kågström; SwedenCpp::Stockholm::0x0F, September 20, 2018
		- https://www.youtube.com/watch?v=1QMHbp5LUKg
- OpenCppCoverage: an open source code coverage tool for C++ under Windows
	- https://github.com/OpenCppCoverage/OpenCppCoverage
- LLVM
	- Clang Source-based Code Coverage
		- https://clang.llvm.org/docs/SourceBasedCodeCoverage.html
	- SanitizerCoverage
		- https://clang.llvm.org/docs/SanitizerCoverage.html
		- A quick tour of LLVM’s Sanitizer coverage
			- https://tech.labs.oliverwyman.com/blog/2017/10/04/a-quick-tour-of-llvms-sanitizer-coverage/
- TestCov: Test execution, coverage measurement, and test-suite reduction
	- https://gitlab.com/sosy-lab/software/test-suite-validator

---

# Reduction

Test-Case Reduction, Minimization

See also: [Debugging](https://github.com/MattPD/cpplinks/blob/master/debugging.md): [Readings](https://github.com/MattPD/cpplinks/blob/master/debugging.md#readings): Delta Debugging

## Reduction - Readings

- Everything You Ever Wanted To Know About Test-Case Reduction, But Didn’t Know to Ask
	- https://blog.trailofbits.com/2019/11/11/test-case-reduction/
- Mitigating (and Exploiting) Test Reduction Slippage
	- A-TEST 2016: International Workshop on Automating Test Case Design, Selection, and Evaluation
	- Josie Holmes, Alex Groce, Mohammad Amin Alipour
	- https://agroce.github.io/atest16.pdf
- Notes on Test-Case Reduction
	- https://www.drmaciver.com/2019/01/notes-on-test-case-reduction/
- Reduce Before You Localize: Delta-Debugging and Spectrum-Based Fault Localization 
	- 2018 IEEE International Symposium on Software Reliability Engineering Workshops (ISSREW)
	- Arpit Christi, Matthew Lyle Olson, Mohammad Amin Alipour, Alex Groce
	- https://doi.org/10.1109/ISSREW.2018.00005
	- https://agroce.github.io/idear18.pdf
- Rust Bug Minimization Patterns
	- http://blog.pnkfx.org/blog/2019/11/18/rust-bug-minimization-patterns/

## Reduction - Software

- C-Reduce
	- "C-Reduce is a tool that takes a large C, C++, or OpenCL file that has a property of interest (such as triggering a compiler bug) and automatically produces a much smaller C/C++ file that has the same property. It is intended for use by people who discover and report bugs in compilers and other tools that process source code."
	- https://embed.cs.utah.edu/creduce/
- Delta Debugging
	- https://www.st.cs.uni-saarland.de/dd/
	- Delta: Heuristically minimizes interesting files
		- http://delta.stage.tigris.org/
		- Minimizing Interesting Files with Delta
			- http://delta.stage.tigris.org/using_delta.html
- halfempty: Fast, Parallel Testcase Minimization
	- https://github.com/googleprojectzero/halfempty
- Shrink Ray: a test-case reducer designed to be effective on a wide range of formats
	- https://github.com/DRMacIver/shrinkray
- Structured Shrinking: Structured shrinking of unknown file formats
	- a program and library that attempts to find structure in a file and uses it to produce smaller examples of the same sort of file.
	- https://github.com/DRMacIver/structureshrink

---

# Software

- Approval Tests for C++
	- https://github.com/approvals/ApprovalTests.cpp
	- https://claremacrae.co.uk/conferences/presentations.html
- Boost.Test
	- http://www.boost.org/libs/test/
	- Production use of Boost.Test 
		- BoostCon 2010; Gennadiy Rozental
		- https://www.youtube.com/watch?v=WUQkn4CnzF4
- [Boost].UT: C++20 μ(micro)/Unit Testing Framework
	- https://github.com/boost-experimental/ut
- Catch2
	- A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD - using C++11, C++14, C++17 and later (or C++03 on the Catch1.x branch) 
	- http://catch-lib.net
	- https://github.com/catchorg/Catch2
	- Modern C++ Testing with Catch2
		- Meeting C++ 2017; Phil Nash
		- https://www.youtube.com/watch?v=3tIE6X5FjDE
	- Modern C++ Testing with Catch2
		- CppCon 2018; Phil Nash
		- https://www.youtube.com/watch?v=Ob5_XZrFQH0
- CUTE: C++ Unit Testing Easier
	- https://cute-test.com/
	- https://github.com/PeterSommerlad/CUTE
- doctest
	- The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD
	- https://github.com/onqtam/doctest
- Google Test
	- https://github.com/google/googletest
- GUnit - Google.Test/Google.Mock/Cucumber on steroids
	- extends/simplifies Google.Test/Google.Mock and adds support for Gherkin (Behaviour Driven Development) to it
	- https://github.com/cpp-testing/GUnit
- OutputCheck: A tool for checking tool output inspired by LLVM's FileCheck
	- https://github.com/stp/OutputCheck
- RapidCheck: QuickCheck clone for C++ with the goal of being simple to use with as little boilerplate as possible.
	- https://github.com/emil-e/rapidcheck
	- https://labs.spotify.com/2015/06/25/rapid-check/

## Software - Test Doubles

Test Doubles: Faking, Mocking

- Fake Function Framework (fff)
	- A testing micro framework for creating function test doubles.
	- https://github.com/meekrosoft/fff
- PowerFake
	- C++ Faking library, which allows faking regular functions, static member functions and non-virtual member functions for testing purposes.
	- https://gitlab.com/hedayat/powerfake
	- https://hedayatvk.wordpress.com/2018/01/22/introducing-powerfake-for-c/

## Software - Test Doubles - Mocking

- FakeIt: a simple mocking framework for C++
	- https://github.com/eranpeer/FakeIt
- Google Mock: The Google C++ mocking framework
	- https://github.com/google/googletest/tree/master/googlemock
	- https://github.com/google/googletest/tree/master/googlemock/docs
- GUnit.GMock
	- GoogleMock without writing and maintaining mocks by hand
	- https://github.com/cpp-testing/GUnit/blob/master/docs/GMock.md
- Hippomocks: Single-header mocking framework
	- https://github.com/dascandy/hippomocks
- Trompeloeil: Header-only C++14 mocking framework
	- https://github.com/rollbear/trompeloeil

---

# Talks

- Google Test Automation Conference (GTAC)
	- https://developers.google.com/google-test-automation-conference/

## Talks - 2019

- Back to Basics: Test-driven Development
	- CppCon 2019; Fedor Pikus
	- https://www.youtube.com/watch?v=RoYljVOj2H8
- Making Testing C++ Binaries Practical @ Facebook Scale: A CI Story
	- CppCon 2019; Mark Isaacson
	- https://www.youtube.com/watch?v=p7xdNjdtojU

## Talks - 2018

- But is it fun? Software Testing in the Video Game Industry
	- ICST 2018
	- Magnus Nordin (Electronic Arts), David King (DICE), and Stefan Posthuma (Electronic Arts)
	- https://www.youtube.com/watch?v=CBIhu_9OolY
- Ensuring Exception Safety Through Testing
	- CppCon 2018; Jon Cohen
	- https://www.youtube.com/watch?v=XPzHNSUnTc4

## Talks - 2017

- C++ Unit testing - the good, the bad & the ugly
	- NDC 2017; Dror Helper
	- https://www.youtube.com/watch?v=EiN3cF_y3vM
	- https://vimeo.com/223984399
	- https://www.slideshare.net/dhelper/c-unit-testing-the-good-the-bad-the-ugly
- Microcontrollers in Micro-increments: A Test-driven C++ Workflow for Embedded Systems
	- CppCon 2017: Mike Ritchie
	- https://www.youtube.com/watch?v=XuHlDtWYeD8
- Mocking C++
	- C++Now 2017; Peter Bindels
	- https://www.youtube.com/watch?v=t0wLm2iiEH0
- Mocking Frameworks considered harmful
	- CppCon 2017; Peter Sommerlad
	- https://www.youtube.com/watch?v=uhuHZXTRfH4

## Talks - 2016

- Assessing software quality from first principles
	- UCIBrenICS Seminar 2016
	- Reid Holmes, University of British Columbia
	- code coverage and mutation testing
	- https://www.youtube.com/watch?v=RIVLHQjpTck

## Talks - 2015

- Advanced Unit Testing in C & C++
	- CppCon 2015; Matt Hargett
	- https://www.youtube.com/watch?v=Wmy6g-aVgZI
- All Your Tests are Terrible: Tales from the Trenches
	- CppCon 2015; T. Winters & H. Wright
	- https://www.youtube.com/watch?v=u5senBJUkPc
- Fast Iteration Tools in the Production of the Talos Principle
	- GDC Europe 2015;  Alen Ladavac 
	- http://www.gdcvault.com/play/1022784/Fast-Iteration-Tools-in-the

## Talks - 2014

- Pragmatic Unit Testing in C++
	- CppCon 2014; Matt Hargett
	- https://www.youtube.com/watch?v=Y8YVSohnlgY