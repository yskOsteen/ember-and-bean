# Ember & Bean Roasters

A responsive, single-page website for **Ember & Bean**, a fictional small-batch coffee roastery that sells fresh-roasted coffee by subscription to homes, offices and cafés.

This project was built as a front-end development exercise: customising an existing Bootstrap template into a complete, working business website.

**Live site:** https://yskosteen.github.io/ember-and-bean/

## About the business

Ember & Bean roasts coffee to order in small batches, buys directly from farmers at fair prices, and delivers fresh to the customer's door. The site presents the brand, its story and values, its coffee subscription plans, and ways to get in touch.

## Features

- Fixed navigation bar with a "More" dropdown and an "Order Now" button
- Hero section with animated, typed headline and animated counters
- Our Story section with the company's values
- Feature cards and a tabbed section (Sourcing, Roasting, Delivery, Support)
- Services grid, call-to-action banner and a customer testimonials slider
- Stats section with animated counters
- Three subscription pricing plans (Home, Office, Café)
- FAQ accordion
- Team slider
- Contact section with a message form, contact details and social links
- Video pop-up ("See How We Roast")
- Scroll animations and a scroll-to-top button
- Fully responsive layout for desktop, tablet and mobile

## Built with

- HTML5
- CSS3
- [Bootstrap 5.3.7](https://getbootstrap.com/) and Bootstrap Icons
- JavaScript, with these libraries:
  - [AOS](https://michalsnik.github.io/aos/) (scroll animations)
  - [Swiper](https://swiperjs.com/) (testimonial and team sliders)
  - [GLightbox](https://biati-digital.github.io/glightbox/) (video pop-up)
  - [Typed.js](https://github.com/mattboldt/typed.js) (typing effect)
  - [PureCounter](https://github.com/srexi/purecounterjs) (animated numbers)
- Google Fonts (Roboto and Raleway)

## Project structure

```
ember-and-bean/
├── index.html          # The main page
├── assets/
│   ├── css/            # Main stylesheet
│   ├── js/             # Main script
│   ├── img/            # Photos and icons
│   └── vendor/         # Bootstrap and other libraries
└── forms/              # Template contact form handler (not active)
```

## Running it locally

1. Clone the repository:
```bash
   git clone https://github.com/yskOsteen/ember-and-bean.git
```
2. Open the folder and double-click `index.html` to view it in your browser.

No build step or installation is needed.

## Known limitations

- The contact form is a template placeholder. It posts to `forms/contact.php`, which needs a server-side script, so it does not send messages.
- The business, team, testimonials, phone number, email and address are fictional and used for demonstration only.
- Social media icons and some footer links are placeholders.

## Credits

- **Template:** [Instant](https://bootstrapmade.com/) by BootstrapMade, used under the [BootstrapMade license](https://bootstrapmade.com/license/). The footer credit link is kept as the license requires.
- **Photos:** stock photography used for demonstration. Add photographer credits here.
- **Customisation and content:** [yskOsteen](https://github.com/yskOsteen)
