1. Assign to the value `6` to the variable `number_six`number_six = 6
  2. What is the datatype of `"Matz"`?
  String
  3. What do the following expressions evaluate to:
    * `"Cool" + "Cool" + "Cool"`
    CoolCoolCool
    * `t = "Troy"
      Troy
      a = "Abed"
      Abed
      "#{t} and #{a} in the Morning"`?
      Troy and abed in the morning
    * `10 * 3`
      30
    * `10 ** 3`
      1000
    * `10 % 3`
      1
    * `10 / 3`
      3
    * `0.7 + 0.1`
      0.799999999
  4. Can you explain why the expressions all give the same result?
    * `"Ronnie " + "Pickering"`
    * `"Ronnie ".+("Pickering")`
    * `"Ronnie ".send(:+, "Pickering")`
    All 3 are just two strings being added together
  5. Please fix the following buggy expressions:
    * `number six = 6`
      number_six=6
    * `"Maroon" + 5`
      "Maroon" + 5.to_s
    * `ture == flase`
      true == false