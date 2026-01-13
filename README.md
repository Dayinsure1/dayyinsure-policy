# Dayinsure Policy Template

## Quick Start

1. Open `config.js` in any text editor
2. Update the values you want to change
3. Save the file
4. Open `policy.html` in a browser to see your changes
5. Deploy all files together to any web host

## Files

| File | Description |
|------|-------------|
| `index.html` | Login page |
| `policy.html` | Policy display page (reads from config.js) |
| `config.js` | **EDIT THIS FILE** - All policy data in one place |
| `dayinsure-logo-new.png` | Logo image |

## Configuration (config.js)

Edit the `config.js` file to update policy information:

```javascript
const policyConfig = {
    // Vehicle Details
    vehicleReg: "LP15 DYU",
    vehicleMakeModel: "PEUGOT 2008 E-HDI ACTIVE",

    // Cover Dates
    coverStartDate: "30 Dec 2025",
    coverStartTime: "16:00",
    coverEndDate: "06 Jan 2026",
    coverEndTime: "16:00",

    // Driver Details
    driverName: "Aaliyah Samuels",
    driverDob: "04 September 2007",

    // Contact Details
    emailAddress: "aaliyah11samuels@icloud.com",
    phoneNumber: "07999682352",
    homeAddress: "31, Elizabeth Road, Newark, Nottinghamshire, NG24 4NP",

    // Cover Information
    coverType: "Comprehensive",
    productType: "Short term motor",
    insurerName: "Aviva",

    // Pricing
    totalPrice: "£349.99",
    excessAmount: "£750",

    // ... more options
};
```

## All Available Config Options

| Property | Description | Example |
|----------|-------------|---------|
| `logoUrl` | Path to logo image | `dayinsure-logo-new.png` |
| `vehicleReg` | Vehicle registration | `LP15 DYU` |
| `vehicleMakeModel` | Vehicle make/model | `PEUGOT 2008 E-HDI ACTIVE` |
| `coverStartDate` | Policy start date | `30 Dec 2025` |
| `coverStartTime` | Policy start time | `16:00` |
| `coverEndDate` | Policy end date | `06 Jan 2026` |
| `coverEndTime` | Policy end time | `16:00` |
| `driverName` | Driver's full name | `Aaliyah Samuels` |
| `driverDob` | Driver's date of birth | `04 September 2007` |
| `emailAddress` | Contact email | `aaliyah11samuels@icloud.com` |
| `phoneNumber` | Contact phone | `07999682352` |
| `homeAddress` | Full home address | `31, Elizabeth Road...` |
| `coverType` | Type of cover | `Comprehensive` |
| `productType` | Product name | `Short term motor` |
| `insurerName` | Insurance company | `Aviva` |
| `totalPrice` | Total policy price | `£349.99` |
| `excessAmount` | Excess amount | `£750` |
| `footerText` | Legal footer text | `Dayinsure™ is a registered...` |

## Deployment

### Netlify Drop (Easiest)
1. Go to https://app.netlify.com/drop
2. Drag the entire `simple-deploy` folder
3. Done! Get your live URL

### Any Web Host
Upload all 4 files to any web server:
- index.html
- policy.html
- config.js
- dayinsure-logo-new.png
