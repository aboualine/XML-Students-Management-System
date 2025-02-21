# Student Management System

## 📌 Description
The **Student Management System** is an Android application designed to manage student records efficiently. It includes authentication, student registration, and CRUD (Create, Read, Update, Delete) operations.

## 🚀 Features
- 🔑 **User Authentication** (Login/Signup)
- 📂 **Manage Student Records** (Add, Update, Delete, View)
- 🎨 **User-Friendly UI** (Material Design)

## 🛠 Technologies Used
- **XML** (UI Design)
- **XSLT** (Styling XML Data)

## 📥 Installation
### Prerequisites
Ensure you have the following installed:
- Android Studio / VS Code with Android Extensions
- Java JDK 17+
- Android SDK

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/aboualine/student-management-system.git
   cd student-management-system
   ```
2. **Open the Project in Android Studio**
3. **Build & Run the Application**
   - Run `gradlew.bat build`

## 🔧 Usage
1. **User Authentication**
   - Register/Login with an email & password.
2. **Manage Students**
   - Add new students with ID, Name, Course, and Year.
   - Edit or Delete student records.
3. **Search & Filter**
   - Find students quickly using the search feature.

## 📜 XML & XSLT Example
```xml
<resources>
    <string name="app_name">Student Management</string>
    <string name="login">Login</string>
</resources>
```
```xslt
<xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
    <xsl:template match="/">
        <html>
            <body>
                <h2>Student Management Strings</h2>
                <table border="1">
                    <tr><th>Key</th><th>Value</th></tr>
                    <xsl:for-each select="resources/string">
                        <tr>
                            <td><xsl:value-of select="@name"/></td>
                            <td><xsl:value-of select="."/></td>
                        </tr>
                    </xsl:for-each>
                </table>
            </body>
        </html>
    </xsl:template>
</xsl:stylesheet>
```

## 🛠 Future Enhancements
- Implement Dark Mode 🌙
- Add Role-Based Access Control 🔐
- Integrate Push Notifications 📩

## 🤝 Contributing
1. **Fork** the repository 🍴
2. **Create a feature branch** (`git checkout -b feature-name`)
3. **Commit changes** (`git commit -m "Added new feature"`)
4. **Push to GitHub** (`git push origin feature-name`)
5. **Create a Pull Request** 🚀

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
💡 **Developed with ❤️ by Aboualine Mohamed**

