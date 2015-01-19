<?php
/**
 * The base configurations of the WordPress.
 *
 * This file has the following configurations: MySQL settings, Table Prefix,
 * Secret Keys, and ABSPATH. You can find more information by visiting
 * {@link http://codex.wordpress.org/Editing_wp-config.php Editing wp-config.php}
 * Codex page. You can get the MySQL settings from your web host.
 *
 * This file is used by the wp-config.php creation script during the
 * installation. You don't have to use the web site, you can just copy this file
 * to "wp-config.php" and fill in the values.
 *
 * @package WordPress
 */

// ** MySQL settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define('DB_NAME', 'database_name_here');

/** MySQL database username */
define('DB_USER', 'username_here');

/** MySQL database password */
define('DB_PASSWORD', 'password_here');

/** MySQL hostname */
define('DB_HOST', 'localhost');

/** Database Charset to use in creating database tables. */
define('DB_CHARSET', 'utf8');

/** The Database Collate type. Don't change this if in doubt. */
define('DB_COLLATE', '');

/**#@+
 * Authentication Unique Keys and Salts.
 *
 * Change these to different unique phrases!
 * You can generate these using the {@link https://api.wordpress.org/secret-key/1.1/salt/ WordPress.org secret-key service}
 * You can change these at any point in time to invalidate all existing cookies. This will force all users to have to log in again.
 *
 * @since 2.6.0
 */
// define('AUTH_KEY',         'put your unique phrase here');
// define('SECURE_AUTH_KEY',  'put your unique phrase here');
// define('LOGGED_IN_KEY',    'put your unique phrase here');
// define('NONCE_KEY',        'put your unique phrase here');
// define('AUTH_SALT',        'put your unique phrase here');
// define('SECURE_AUTH_SALT', 'put your unique phrase here');
// define('LOGGED_IN_SALT',   'put your unique phrase here');
// define('NONCE_SALT',       'put your unique phrase here');

define('AUTH_KEY',         ';U=}|r1TW[PdXk2.pWk@FIcfm__<- M%KV :,X-j=nseYabgpMFqw}E?[!ZeXf92');
define('SECURE_AUTH_KEY',  '-~0b6&C8X?UHsdU~fYnuNOB,_SNg^|UK$k{9^+pNPaJkvWGN>x.4Xe+jVDR:BO<K');
define('LOGGED_IN_KEY',    'r0++3MW@/Yb57LOanP=Z{jI.2&TJ/a^}rKyf+}87w6@,eViY3Vxrq1-:XgO+hk+T');
define('NONCE_KEY',        'kiq|ZXRCr=FEpxG-+|bwR~L>,%^@@#==%0@G8&fQA tv,:CITBuU;]UJa=EHRUt@');
define('AUTH_SALT',        '+hJeW:&9Ehz~NZ^+T9m3|H{>}V,=g6p}6--(&b!]w%`,1|RSR-9HK0^2$bH)b6_Q');
define('SECURE_AUTH_SALT', 'gO5}BSCq-;LiQw9B=x@GY)(Bygc:Ly~H 4By%FeziC^]yGO_PDrl>[C $^eo-sNQ');
define('LOGGED_IN_SALT',   ']uf4w*-F[IO86sq2*%l5dd~%v`7|,{2->@6Ebq!&Pnsfen.]_nGAlR+||22i^ExE');
define('NONCE_SALT',       'L|-BZ:k-0-}ZL!-YQWgWA7|l<m-N>vL|;W`&.rZb>m+#)2)d091q6>7oJ6h&.(h9');

/**#@-*/

/**
 * WordPress Database Table prefix.
 *
 * You can have multiple installations in one database if you give each a unique
 * prefix. Only numbers, letters, and underscores please!
 */
$table_prefix  = 'wp_';

/**
 * For developers: WordPress debugging mode.
 *
 * Change this to true to enable the display of notices during development.
 * It is strongly recommended that plugin and theme developers use WP_DEBUG
 * in their development environments.
 */
define('WP_DEBUG', false);

/* That's all, stop editing! Happy blogging. */

/** Absolute path to the WordPress directory. */
if ( !defined('ABSPATH') )
	define('ABSPATH', dirname(__FILE__) . '/');

/** Sets up WordPress vars and included files. */
require_once(ABSPATH . 'wp-settings.php');
