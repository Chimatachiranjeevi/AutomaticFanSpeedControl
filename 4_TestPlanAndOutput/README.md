# **TESTPLAN AND OUTPUT**
 ## **HIGH LEVEL TEST PLAN**
 <html>
<body>
<!--StartFragment-->

Test_ID | Test Cases Descripation | Expected O/P | Actual O/P | Status
-- | -- | -- | -- | --
TD_01 | Shall have to Implement the code for Microcontroller | Passed | Success | Done ✅
TD_02 | Microcontroller code shall run without any errors | Passed | Success | Done ✅
TD_03 | Circuit of the project shall Implement in Simulide | Passed | Success | Done ✅
TD_04 | Circuit of the project shall simulate without errors | Passed | Success | Done ✅

<!--EndFragment-->
</body>
</html>

<html>
<body>
<!--StartFragment--><h2 dir="auto" style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; font-size: 1.5em; font-weight: 600; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid var(--color-border-muted); color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><strong style="box-sizing: border-box; font-weight: 600;">LOW LEVEL TEST PLAN</strong></h2>

Test_ID | Test Cases Descripation | Input | Expected O/P | Actual O/P | Status
-- | -- | -- | -- | -- | --
TD_01 | Temperature(LM35) | 6 | Display on LCD | Display on LCD | Done ✅
TD_02 | Temperature(TC74) | 32 | Display on LCD | Display on LCD | Not Done
TD_03 | Automatic Mode | Temp<10 | Fanspeed=0 | Fanspeed=0 | Done ✅
TD_04 | Automatic Mode | Temp<20 | Fanspeed=1 | Fanspeed=1 | Done ✅
TD_05 | Automatic Mode | Temp>20 | Fanspeed=2 | Fanspeed=2 | Done ✅

<!--EndFragment-->
</body>
</html>

# **SIMULID OUTPUT**

![image](https://user-images.githubusercontent.com/101035721/164610325-7d373592-2caf-40ba-8cd4-ede399fb6ee5.png)

![image](https://user-images.githubusercontent.com/101035721/164610361-0972208c-dd19-4740-8ecd-93fa859050a8.png)

![image](https://user-images.githubusercontent.com/101035721/164610385-8acca998-a8ee-4730-b974-be01ea0fce1a.png)

![image](https://user-images.githubusercontent.com/101035721/164610409-4885411e-9f4a-492a-8955-a0fefa3e2eae.png)