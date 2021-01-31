topic:
     Leverage Android Automated Testing to Assist Crowdsourced Testing
abstract:
     Crowdsourced testing is an emerging trend in the mobile application testing paradigm. In company with conducting large-scale user-oriented testing scenarios in diverse mobile devices, crowdsourced testing also brings the problem of crowdworkers with different testing skills, which significantly slows down the quality of crowdsourced testing.
     Despite massive approaches to assisting crowdsourced testing, there is still a lack of assistance for crowdworkers. That is, the existing approaches lack a way to guide crowdworkers to test the App Under Test (AUT) during crowdsourced testing.
     In this paper, we propose a test assistance mechanism by leveraging Android automated testing (i.e., dynamic analysis and static analysis). Such a test assistance mechanism is designed to assist crowdworkers in quickly getting familiar with and understanding the AUT, and thereby discovering bugs of the AUT during crowdsourced testing.
     Our approach combines dynamic analysis and static analysis to construct an Annotated Window Transition Graph (AWTG) model of the AUT. Based on the AWTG model, our approach automatically extracts test tasks for crowdworkers, recommends these test tasks to crowdworkers, and further guides crowdworkers to complete these test tasks.
     We conduct evaluations on ten real-world Android apps, and the experimental results demonstrate that our approach can effectively and efficiently assist crowdworkers in testing the AUT during crowdsourced testing.Moreover, the results from a user study indicate that our approach is useful to assist crowdsourced testing.
process:
    1. First install APP Cloud Read, make sure the installed APP has a boot plug-in
    2. Start running the server program BugHunter, and start execution through the command spring-boot:run
    3. The test data in Bughunter comes from the data in SQL
    4. CloudReader-master is the source code with plugin
    5. CloudReader-master source code address https://github.com/youlookwhat/CloudReader.git
other:
    The data of other tested apk is still being processed
   