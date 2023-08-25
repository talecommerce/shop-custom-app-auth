This is meant for custom Shopify apps that just need to get a access token, without creating entire backend.

Usage:

1. Note Client ID & Client Secret of the app
2. Set App URL to: https://talecommerce.github.io/shopify-oauth-helper?client_id={client_id}&access_scope={scopes_seperated_by_comma}
3. Add Allowed redirection URL(s): https://talecommerce.github.io/shopify-oauth-helper
4. Open or Install the app
5. Open browser console and click redirect link
6. Open browser console and copy cURL request to grab access token
7. In the cURL request body, set Client Secret to your app secret