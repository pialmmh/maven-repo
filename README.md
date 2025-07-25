# 📦 Public Maven Repository for ShardingSphere Fat JAR

This repository hosts the **ShardingSphere All-in-One Fat JAR (version 5.5.3)** as a publicly available Maven artifact via GitHub Pages.

---

## ✅ How to Use

Add the following to your Maven project's `pom.xml`:

```xml
<repositories>
  <repository>
    <id>pialmmh-github-repo</id>
    <url>https://pialmmh.github.io/maven-repo</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>org.apache.shardingsphere</groupId>
    <artifactId>shardingsphere-all-in-one</artifactId>
    <version>5.5.3</version>
  </dependency>
</dependencies>
```

---

## 📄 Artifact Details

- **Group ID**: `org.apache.shardingsphere`  
- **Artifact ID**: `shardingsphere-all-in-one`  
- **Version**: `5.5.3`  
- **Packaging**: `jar`

---

## 🌍 Repository URL

👉 [https://pialmmh.github.io/maven-repo](https://pialmmh.github.io/maven-repo)

This URL serves as a public Maven repository that can be used in any project to resolve the fat JAR dependency.
