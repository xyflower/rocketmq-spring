## What is the purpose of the change

XXXXX

## Brief changelog

XX

## Verifying this change

XXXX

Follow this checklist to help us incorporate your contribution quickly and easily. Notice, `it would be helpful if you could finish the following 5 checklist(the last one is not necessary)before request the community to review your PR`.

- [ ] Make sure there is a [Github issue](https://github.com/apache/rocketmq/issues) filed for the change (usually before you start working on it). Trivial changes like typos do not require a Github issue. Your pull request should address just this issue, without pulling in other changes - one PR resolves one issue. 
- [ ] Format the pull request title like `[ISSUE #123] Fix UnknownException when host config not exist`. Each commit in the pull request should have a meaningful subject line and body.
- [ ] Write a pull request description that is detailed enough to understand what the pull request does, how, and why.
- [ ] Write necessary unit-test(over 80% coverage) to verify your logic correction, more mock a little better when cross module dependency exist. 
- [ ] Run `mvn -B clean apache-rat:check findbugs:findbugs checkstyle:checkstyle` to make sure basic checks pass. Run `mvn clean install -DskipITs` to make sure unit-test pass. Run `mvn clean test-compile failsafe:integration-test`  to make sure integration-test pass.
- [ ] If this contribution is large, please file an [Apache Individual Contributor License Agreement](http://www.apache.org/licenses/#clas).
