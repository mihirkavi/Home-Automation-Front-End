# Home-Automation-Front-End

Static front-end mockup for a home automation (IoT) dashboard, built with HTML, CSS and
Bootstrap 3.

## What's inside

Three pages that share a responsive navigation bar (Home, Security, Appliances, plus
Sign Up / Login links) and a footer:

- `JD_iot.html`: home page with a "Status" section (fans, lights, AC)
- `security.html`: "Control" section for the front door, fire alarm, code lock and garage
- `appliances.html`: section for fans, lights and AC

The pages are layout only: there is no JavaScript logic or connection to any devices or
back end.

## Project structure

```
JD_IOT/
  JD_iot.html        JD_iot_style.css
  security.html      security.css
  appliances.html    appliances.css
```

## Tech stack

HTML, CSS, Bootstrap 3.3.7, jQuery 3.1.1 and Google Fonts (loaded from CDNs).

## Getting started

No build step is needed. Open `JD_IOT/JD_iot.html` in a browser (an internet connection
is required for the CDN assets).

## Status

Student prototype from March 2017; not actively maintained.

## License

Released under the MIT License. See [LICENSE](LICENSE).
