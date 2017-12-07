# Addressy (Postcode Anywhere)
## Modified for Ionic and Angular

Copyright © 2009-2017 Postcode Anywhere (Holdings) Ltd. (http://www.postcodeanywhere.co.uk)

This script is provided to Addressy users to include in their site. The `pca.getElement` function, however, gets an element by ID or the first element by name, which is incompatible with how ionic renders forms. The `ion-button`, acting as a wrapper, and the `input` field both share these properties. I have modified this function so it correctly maps to ionic generated forms.
