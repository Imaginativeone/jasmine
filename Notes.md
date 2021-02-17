- [ ] Jasmine JavaScript Testing - Second Edition
  - [ ] 01 Getting Started with Jasmine
  - [ ] 02 Your First Spec
    - [ ] The Investment Tracker Application
      - To get started, we need an example scenario: consider that you are developing an application to track investments in the stock market.
    - [ ] Jasmine basics and thinking in BDD
    - [ ] Setup and teardown
    - [ ] Nested describes
      - [ ] Setup and teardown
      - There are still three more acceptance criteria to be implemented. The next in the list is:
      "Given an investment, it should have the invested shares quantity."
      - Writing it should be as simple as the previous spec was. In the spec/InvestmentSpec.js file, you can translate this criterion into a new spec, called 
      "should have the invested shares quantity:
      ```javascript
      describe("Investment", function() {
        it("should be of a stock", function() {
          let stock = new Stock();
          let investment = new Investment({
            stock: stock,
            shares: 100
          });
        });
        expect(investment.stock).toBe(stock);
      });
      ```
      - 
      - [ ] Coding a spec with shared behavior
      - [ ] Understanding matchers
        - [ ] Custom matchers
        - [ ] Built-in matchers
          - [ ] The toEqual built-in matcher
          - [ ] The toBe built-in matcher
    - [ ] Summary
  - [ ] 03 Testing Frontend Code
  - [ ] 04 Asynchronous Testing AJAX
  - [ ] 05 Jasmine Spies
  - [ ] 06 Light Speed Unit Testing
  - [ ] 07 Testing React Applications
  - [ ] 08 Build Automation
