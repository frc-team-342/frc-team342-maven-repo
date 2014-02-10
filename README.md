frc-team342-maven-repo
======================

FRC Team 342 Official Maven Artifact Repository

## Usage

### Release Builds
```
<repositories>
...
    <repository>
        <id>first-team342-maven-repo-releases</id>
        <name>FIRST Team 342 Maven Repo - Releases</name>
        <url>https://raw.github.com/frc-team-342/frc-team342-maven-repo/master/releases</url>
        <releases>
            <checksumPolicy>fail</checksumPolicy>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>false</enabled>
        </snapshots>
    </repository>
...
</repositories>
```

### Snapshot Builds
```
<repositories>
...
  <repository>
      <id>first-team342-maven-repo-snapshots</id>
      <name>FIRST Team 342 Maven Repo - Snapshots</name>
      <url>https://raw.github.com/frc-team-342/frc-team342-maven-repo/master/snapshots</url>
      <releases>
          <enabled>false</enabled>
      </releases>
      <snapshots>
          <checksumPolicy>fail</checksumPolicy>
          <enabled>true</enabled>
      </snapshots>
  </repository>
...
</repositories>
```
