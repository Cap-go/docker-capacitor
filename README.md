# docker-capacitor

<a href="https://capgo.app/"><img src='https://raw.githubusercontent.com/Cap-go/capgo/main/assets/capgo_banner.png' alt='Capgo - Instant updates for capacitor'/></a>

<div align="center">
  <h2><a href="https://capgo.app/?ref=plugin"> ➡️ Get Instant updates for your App with Capgo</a></h2>
  <h2><a href="https://capgo.app/consulting/?ref=plugin"> Missing a feature? We’ll build the plugin for you 💪</a></h2>
</div>

🐳 Docker image for building Ionic apps with Capacitor. 

## How to use this image

### Pull image

Pull from GitHub Container Registry:  

```
docker pull capgo/capacitor:latest
```

### Build image

Build from GitHub:  

```
docker build -t Cap-go/docker-capacitor https://github.com/robingenz/docker-capacitor.git#main
```

Available build arguments:  

- JAVA_VERSION (Default: `21`)
- NODEJS_VERSION (Default: `24`)
- ANDROID_SDK_VERSION (Default: `11076708`)
- ANDROID_BUILD_TOOLS_VERSION (Default: `34.0.0`)
- ANDROID_PLATFORMS_VERSION (Default: `34`)
- GRADLE_VERSION (Default: `8.2.1`)
- IONIC_VERSION (Default: `7.2.0`)
- CAPACITOR_VERSION (Default: `7.4.3`)

### Run image

Run the docker image:  

```
docker run -it Cap-go/docker-capacitor bash
```

## Questions / Issues

If you got any questions or problems using the image, please visit my [GitHub Repository](https://github.com/Cap-go/docker-capacitor) and write an issue.

Credit: original work from Capawesome we forget to served Capgo users https://github.com/capawesome-team/docker-ionic-capacitor
