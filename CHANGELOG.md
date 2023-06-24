# ulidx changelog

## v2.0.0
_2023-06-04_

 * Multiple builds for different environments:
   * Node ESM
   * Node CJS
   * Browser ESM
   * Browser CJS
 * [#24](https://github.com/perry-mitchell/ulidx/pull/24): Add `globalThis` to support Vercel Edge runtime

## v1.0.0
_2023-05-03_

 * ESM
   * CommonJS/ESM builds
 * Node 16 minimum
 * **Bugfixes**:
   * [#19](https://github.com/perry-mitchell/ulidx/issues/19): `decodeTime` fails on lower-case ULIDs

## v0.5.0
_2023-02-12_

 * `fixULIDBase32` method for cleaning up ULIDs by checking their Base32 encoding

## v0.4.0
_2022-12-31_

 * `isValid` utility for checking for valid ULIDs

## v0.3.0
_2022-01-01_

 * **Bugfixes**:
   * [#4](https://github.com/perry-mitchell/ulidx/issues/4): `ulid` error in Node REPL

## v0.2.0
_2021-09-24_

 * `decodeTime` helper

## v0.1.0
_2021-06-05_

 * Initial release

