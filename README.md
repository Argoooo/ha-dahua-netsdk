# Home Assistant Dahua NetSDK Bridge

A small bridge that allows Home Assistant to control Dahua cameras using Dahua's NetSDK.

This project started because newer Dahua consumer cameras (such as the **DH-H4C-P**) don't expose ONVIF PTZ or the older CGI API, making them difficult to integrate with Home Assistant. Since SmartPSS can control these cameras locally through the NetSDK, this project aims to expose the same functionality in a simple and reusable way.

> **Project Status:** 🚧 Work in progress

## Planned Features

- Camera login
- PTZ controls (Pan/Tilt)
- REST API
- Docker support
- Home Assistant integration
- HACS support

## Tested Devices

| Camera | Status |
| ------- | ------ |
| DH-H4C-P | 🚧 In Progress |

If you have another Dahua camera that uses the NetSDK, feel free to test it and let us know.

## Roadmap

- [x] Load Dahua NetSDK
- [x] Initialize SDK
- [ ] Login to camera
- [ ] PTZ controls
- [ ] REST API
- [ ] Docker image
- [ ] Home Assistant integration
- [ ] HACS support

## Project Structure

```
dahua-ha-bridge/
├── sdk/
├── dahua/
├── api/
├── examples/
├── tests/
└── README.md
```

## Disclaimer

This project is not affiliated with Dahua Technology. It is an independent community project.

## License

MIT
