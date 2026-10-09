Self Practice Android — Build নির্দেশনা

১. ZIP ফাইল Extract করো।
২. GitHub repository-তে এই ফোল্ডারের ভেতরের সব ফাইল ও ফোল্ডার আপলোড করো।
   খেয়াল রাখবে, repository root-এ app/, build.gradle, settings.gradle এবং .github/ থাকবে।
৩. GitHub-এর Actions ট্যাবে Build Self Practice APK workflow চালু হবে। চাইলে Run workflow ব্যবহার করতে পারো।
৪. Build সফল হলে Self-Practice-APK artifact ডাউনলোড করো। ZIP artifact-এর ভেতরে app-debug.apk থাকবে।

Build environment: JDK 17, Gradle 8.9, Android Gradle Plugin 8.7.3, compileSdk 35.
মূল HTML পেজ এবং profile_logo.png অপরিবর্তিত রাখা হয়েছে; পেজের নিচে Hasnat-এর Facebook লিংকসহ copyright line যোগ করা হয়েছে।

নোট: GitHub Actions-এ প্রথমবার Android SDK components ডাউনলোড হতে পারে। Build সফল হয়েছে কি না Actions log থেকেই নিশ্চিত হবে।
