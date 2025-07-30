# Australian Facilities TAK Plugin

A Team Awareness Kit (TAK) plugin for Australian Emergency Facilities, providing quick access to emergency facility locations across Australia.

## Prerequisites & Setup

### Step 1: Install ATAK

- **From Google Play Store** 
- **From TAK.gov** 
- Requires ATAK version 5.4.0 or higher

### Step 2: Setup Maps (if never used ATAK before)

1. Download basemaps from [Joshua Fuller's ATAKMaps repository](https://github.com/joshuafuller/ATAKMaps)
2. Import the downloaded .zip files into ATAK:
   - Open ATAK
   - Navigate to **Import Manager**
   - Select the basemap .zip files
3. DTED0 will automatically download. For better height data, use DTED2 data for your area of interest)

### Step 3: Install AAHS Icon Pack

1. Download `AAHS.zip` from this repository
2. In ATAK, navigate to:
   - **Point Dropper** menu
   - **Settings** → **Add Iconset**
3. Select the downloaded `AAHS(1).zip` file
4. Australian emergency facility icons are now available

### Step 4: Install AusEmergFac Plugin

1. Download the **Aus Facilities ATAK Plugin** APK from this repo or from the Google Play Store
2. The plugin will automatically integrate with ATAK
3. Restart ATAK if prompted

## Usage

1. **Enable the plugin** in ATAK (if not auto-enabled):
   - Hamburger menu → Plugins → Enable/Load the plugin

2. **Access emergency facilities**:
   - Click on the Australian Facilities plugin icon
   - Apply relevant search filters:
     - Facility type (Airport, Fire Station, Police, etc.)
     - X km Distance, or closest 10 based on location of ATAK EUD.

3. **View facilities** on the map with appropriate AAHS icons

## Files in This Repository

- `AAHS.zip` - Icon set for Australian emergency facilities
- `PRIVACY_POLICY.md` - Privacy policy for the plugin
- `README.md` - This file
- ATAK-Plugin-AusEmergFacPlugin ...APK.    (alternate to PlayStore Download)

## Support

For plugin-specific issues:
- Create an issue in this repository

For general ATAK support:
- [TAK Community Discord](https://discord.com/invite/xTdEcpc)

## Privacy Policy

This plugin does not collect any personal data. For full details, see our [Privacy Policy](PRIVACY_POLICY.md).

## Acknowledgements, Data Sources & Attribution
- The TAK Product Center for the TAK ecosystem
- Joshua Fuller for ATAKMaps repository
- **Icon Set**: Emergency Management Spatial Information Network Australia (EMSINA) - [Australian All Hazards Symbol Set](https://www.emsina.org/australian-all-hazards-symbol-set/assets)
- **Facility Data**: Emergency Management Facilities Database - [Geoscience Australia](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/147776)
- **Airport Locations**: [OpenAIP.net](https://www.openaip.net)

---

**Note:** This plugin is not officially affiliated with or endorsed by the TAK Product Center or Australian emergency services.
