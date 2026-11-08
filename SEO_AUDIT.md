# Funngro Website – SEO Audit Report

**Project:** Funngro Teen and Company Pages Redesign  
**Deployment:** GitHub Pages

## 1. Deployed Website URLs

- **Teen Page:** https://yogavardhan.github.io/funngro-website/
- **Company Page:** https://yogavardhan.github.io/funngro-website/companies.html

## 2. PageSpeed Insights Results

| Category | Teen Page | Company Page |
|---|---:|---:|
| Performance | 100 | 100 |
| Accessibility | 100 | 100 |
| Best Practices | 100 | 77 |
| SEO | 100 | 100 |

**Agentic Browsing:** 2/2 (reported result).

## 3. Audit Findings

### Teen Page
The Teen page achieved 100 in all four Lighthouse categories:
- Performance
- Accessibility
- Best Practices
- SEO

### Company Page
The Company page achieved:
- Performance: 100
- Accessibility: 100
- Best Practices: 77
- SEO: 100

**Best Practices warning:**

PageSpeed Insights reported:

"Does not use HTTPS – 1 insecure request found."

The identified URL was:

`mailto:hello@funngro.com`

The request resolution was reported as "Allowed with warning".

A `mailto:` link opens the visitor's email application. It is not an HTTP resource and does not, by itself, indicate insecure HTTP delivery or mixed content.

**Recommendation:** Retain the email contact link because it provides useful functionality. Document this finding as a Lighthouse warning associated with the email URI.

## 4. Overall Assessment

Both pages achieved 100 in Performance, Accessibility and SEO.

The Teen page achieved a perfect score across all four Lighthouse categories. The Company page received 77 in Best Practices because of the reported email URI warning.

Overall, the results indicate strong performance across the tested categories.

## 5. Recommendations

1. Continue serving both pages over HTTPS.
2. Retain the working email contact link.
3. Re-run PageSpeed Insights after future website changes.
4. Review any new audit warnings individually.
5. Retain screenshots of both PageSpeed reports as project evidence.

## 6. Audit Scope and Limitations

This report is based on PageSpeed Insights results provided by the project owner. It is not an independent full technical SEO audit.

Google Search Console indexing, backlinks, search rankings, analytics configuration and field Core Web Vitals have not been independently verified.

---

**Project:** Funngro Website Redesign  
**Hosting:** GitHub Pages
