# REST API Static Security Testing

This Jenkins plugin lets you add automated static application security testing (SAST) on API contract files to your Jenkins CI/CD pipeline.

API contracts must be in OpenAPI (aka Swagger) format. Both JSON and YAML formats, and both OASv2 and v3 are supported.

The extension is powered by 42Crunch API Contract Security Audit. Security Audit performs a static analysis that includes more than 200 checks on your API definitions. The audit checks the format, best practices, as well as potential vulnerabilities in the way your APIs define authentication, authorization, transport, and data coming in and going out. For more details, see [API Security Encyclopedia](https://apisecurity.io/encyclopedia/content/api-security-encyclopedia.htm).

You can create a free 42Crunch account at https://platform.42crunch.com/register, and then follow the [instructions to configure the extension](https://docs.42crunch.com/latest/content/tasks/integrate_jenkins.htm).
