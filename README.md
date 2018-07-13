# pg-error-codes

A list of error codes in PostgreSQL, exposed as JSON. Published as an `npm` package.

Last updated for PostgreSQL 10.4.

## Usage

```bash
$ npm install --save pg-error-codes
```

```javascript
import errorCodes from 'pg-error-codes';

console.log(errorCodes);
// {
//   "00000": "successful_completion",
//   "01000": "warning",
//   ... etc ...
```

## License

Public Domain

## Sources

[Appendix A. PostgreSQL Error Codes](https://www.postgresql.org/docs/10/static/errcodes-appendix.html)
