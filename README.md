
const pool = mysql.createPool({
    host: 'cfif31.ru',
    database: 'ISPr25-24_StreltsovEV_rzd',
    user: 'ISPr25-24_StreltsovEV',
    password: 'ISPr25-24_StreltsovEV', 
    port: 3306,
    waitForConnections: true,
    connectionLimit: 10,
    queueLimit: 0,
    ssl: {
        rejectUnauthorized: false
    }
});