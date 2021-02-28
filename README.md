# unit_test basic theory

**@RunWith(AndroidJUnit4::class)**
 In general, Junit library is used to test java or kotlin code or any code runs on the jvm basically and *here (instrumented unit test)* we are not inside of such a plain java cotton enviriment, we are inside of an android environment, we run test on the android emulator and not on the jvm, those are instrumented unit tests and they run on the android emulator because the need android component. **This anotation** just make sure that all these tests in side the class run on emulator, or just tell that these tests are instrumented unit test

**@SmallTest**
**@MediumTest**
**@LargeTest**
