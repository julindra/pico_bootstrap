# Pico Bootstrap

### Screenshot
Header
<img src="http://renhard.net/github/pico_bootstrap/pico_bootstrap-header.png" alt="Pico Bootstrap theme" width="500px">
Footer
<img src="http://renhard.net/github/pico_bootstrap/pico_bootstrap-footer.png" alt="Pico Bootstrap theme" width="500px">

### About
Bootstrap 3 theme for PicoCMS. Suitable for Pico 0.9.

### Instalation
1. [Download](https://github.com/julindra/pico_bootstrap/archive/master.zip).
2. Extract and copy folder `pico_bootstrap` to your Pico `themes` folder.
3. Open your `config/config.php`, and edit the theme to this line:
    <pre>$config['theme'] = 'pico_bootstrap';</pre>
4. Add this lines to add the social media button at the footer of your site (If you don't need the social media button, just skip this step).
    <pre>
    $config['soc_media'] = array(
        'facebook' => 'https://www.facebook.com/JulindraRenhard', 
        'twitter' => 'https://twitter.com/julindrarenhard',
    	'instagram' => 'https://instagram.com/julindrarenhard',
    	'youtube' => 'https://www.youtube.com/user/r3nhardj96',
    	'google' => 'https://plus.google.com/+RenhardJulindra',
    	'linkedin' => 'https://id.linkedin.com/pub/renhard-julindra-jacob/71/846/495',
    	'pinterest' => 'https://id.pinterest.com/'
    );
    </pre>
    Note: You need to change the URL to your social media profile URL. You can change the order or remove the social media that you want to remove. 
5. That's it.

### About Bootstrap
Sleek, intuitive, and powerful front-end framework for faster and easier web development.

http://twitter.github.io/bootstrap/


### About Pico
Pico is a stupidly simple, blazing fast, flat file CMS. See http://pico.dev7studios.com for more info.