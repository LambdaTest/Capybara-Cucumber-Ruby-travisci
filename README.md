# Run Capybara Cucumber Ruby Tests on TestMu AI (Formerly LambdaTest)

<p align="center">
  <a href="https://www.testmuai.com/"><img src="https://img.shields.io/badge/MADE%20BY%20TestMu%20AI-000000.svg?style=for-the-badge&labelColor=000" alt="Made by TestMu AI"></a>
  <a href="https://community.testmuai.com/"><img src="https://img.shields.io/badge/Join%20the%20community-blueviolet.svg?style=for-the-badge&labelColor=000000" alt="Community"></a>
</p>

## Getting Started

TestMu AI (Formerly LambdaTest) is an AI-native, multi-agent quality engineering platform. Use this sample to run your Capybara Cucumber Ruby tests on the TestMu AI (Formerly LambdaTest) cloud.

- [Sign up on TestMu AI](https://www.testmuai.com/register/) (Formerly LambdaTest).
- Follow the [TestMu AI Documentation](https://www.testmuai.com/support/docs/) for the full setup walkthrough.

### Environment Setup
 * For Windows
     You can download Ruby for Windows from http://rubyinstaller.org/
     Run the installer and follow the setup wizard to install Ruby.

 * For Linux/Mac: 
     Download RVM and install Ruby: curl -L https://get.rvm.io | bash -s stable --ruby
     
## TestMu AI (Formerly LambdaTest) Credentials
   * Set TestMu AI (Formerly LambdaTest) username and access key in environment variables.
   
   example:
 * For linux/mac    
    ```
    export LT_USERNAME="YOUR_USERNAME"
    export LT_ACCESS_KEY="YOUR ACCESS KEY"
    ```
 * For Windows
    ```
    set LT_USERNAME="YOUR_USERNAME"
    set LT_ACCESS_KEY="YOUR ACCESS KEY"
    ```
## Setup
 * Clone the repo
 * Install dependencies `bundle install`
 * Update `*.config.yml` files inside the `config/` directory with your TestMu AI (Formerly LambdaTest) Username and Access Key

### Running your tests
 * To run a single test, run `bundle exec rake single`
 * To run local tests, run `bundle exec rake local`
 * To run parallel tests, run `bundle exec rake parallel`

#####  Routing traffic through your local machine
- Set tunnel value to `true` in test capabilities
> OS specific instructions to download and setup tunnel binary can be found in the [TestMu AI Documentation](https://www.testmuai.com/support/docs/local-testing-for-windows/).

## Notes
 * You can view your test results on the TestMu AI (Formerly LambdaTest) Automate dashboard
 * To test on a different set of browsers, check out the TestMu AI (Formerly LambdaTest) capabilities generator

### Resources

##### [SeleniumHQ Documentation](http://www.seleniumhq.org/docs/)
##### [Capybara Documentation](https://www.rubydoc.info/github/jnicklas/capybara)
##### [Ruby Documentation](https://ruby-doc.org/)
##### Travis CI Documentation (see [TestMu AI Documentation](https://www.testmuai.com/support/docs/))

## LambdaTest is Now TestMu AI

On **January 12, 2026**, [LambdaTest evolved to TestMu AI](https://www.testmuai.com/lambdatest-is-now-testmuai/), the world's first fully autonomous **Agentic AI Quality Engineering Platform**.

Same team. Same infrastructure. Same customer accounts. All existing LambdaTest logins, scripts, capabilities, and integrations continue to work without change.

ð Find the new home for [LambdaTest](https://www.testmuai.com).

### How LambdaTest Evolved into TestMu AI

In 2017, we launched LambdaTest with a simple mission: make testing fast, reliable, and accessible. As LambdaTest grew, we expanded into Test Intelligence, Visual Regression Testing, Accessibility Testing, API Testing, and Performance Testing, covering the full depth of the testing lifecycle.

As software development entered the AI era, testing had to evolve, too. We rebuilt the architecture to be AI-native from the ground up, with autonomous agents that **plan, author, execute, analyze, and optimize tests** while keeping humans in the loop. The platform integrates with your repos, CI, IDEs, and terminals, continuously learning from every code change and development signal.

That evolution earned a new name: **TestMu AI**, built for an AI-first future of quality engineering. TestMu is not a new name for us. It is the name of our annual community conference, which has brought together 100,000+ quality engineers to discuss how AI would reshape testing, long before that became an industry norm. 

What started as a high-performance cloud testing platform has transformed into an AI-native, multi-agent system powering a connected, end-to-end quality layer. That evolution defined a new identity: LambdaTest evolved into TestMu AI, built for an AI-first future of quality engineering.

## Support

Got a question? Email [support@testmuai.com](mailto:support@testmuai.com) or chat with us 24x7 from our chat portal.
