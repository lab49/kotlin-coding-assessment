# Lab49 Mobile Coding Exercise

Welcome to the Lab49 Android coding exercise. Please read this document carefully and complete the setup steps **before** your interview begins.

---

## Prerequisites

You will need the following installed and working on your machine before the interview.

### Android Studio

Download and install the latest stable release of **Android Studio** from:
https://developer.android.com/studio

Android Studio bundles a JDK and the Android SDK Manager — both are required.

During or after installation, use the **SDK Manager** (Settings > Languages & Frameworks > Android SDK) to install:

- **Android SDK Platform 37** (API level 37)
- **Android SDK Build-Tools 37.0.0**
- **Android Emulator** (if you plan to run the app on a virtual device)

### Java 21

The project uses a JVM toolchain targeting Java 21. Android Studio ships with a suitable JDK, but verify by running:

```
java -version
```

You should see `openjdk 21` (or higher). If not, install JDK 21 from https://adoptium.net and ensure it is on your `PATH`.

## Recommended Device Setup

To run the app on a device during the interview, set up one of the following ahead of time:

**Android Emulator (recommended):** In Android Studio, open the **Device Manager** (View > Tool Windows > Device Manager) and create a virtual device running API level 28 or higher.

**Physical device:** Enable **Developer Options** and **USB Debugging** on your Android device and connect it via USB.

---

## Project Setup

Download the project zip file from the URL provided by your recruiter to a local directory. The zip file is password-protected — the password will be provided at the start of your interview.

---

## Questions?

If you have any trouble getting the project to build before the interview, please reach out to your recruiter so we can help you resolve it ahead of time.
