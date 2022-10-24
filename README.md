# all-in-one-wp-migration.6.77


From the constants.php file serach the text
## define( 'AI1WM_MAX_FILE_SIZE', 2 << 28 );
Replace this Code
# define( 'AI1WM_MAX_FILE_SIZE', 4294967296 * 10 );
