# Java Source Code Analysis

Vulnerabilities can be detected by searching the following keywords in vulnerable web applications written in Java:

## Command Injection

ProcessBuilder

Runtime.getRuntime().exec

runtime.exec

## XSS
out.print

## File Inclusion
import url=

## Path Manipulation
new File

## SQL Injection
executeQuery

executeUpdate

## XPATH Injection
xPath.compile

## DOS
Pattern.compile

## CSRF Injection
setHeader

## Log Forging
logger

## File Upload
<input type="file" id="file"/>

## XML External Entity Injection
builder.parse
