# Benchmark mapping
OWASP/LLM findings from BENCH.json; ML-TRL: N/A (not an ML model).
```json
{
  "schema": "anticloud.tier-bench/1",
  "project": "FASHION_MNIST",
  "source": {
    "repo_path": "E:\\fenta\\Downloads\\The Anticloud\\ANTICLOUD_REPOS\\CLOTHING_RETAIL\\FASHION_MNIST\\UPSTREAM_CLONE",
    "git": {
      "head": "",
      "url": "https://github.com/the-anticloud/OPENMRS_CORE.git",
      "branch": "master",
      "committed_at": "2026-09-29T11:06:59+04:00"
    }
  },
  "metrics": {
    "files_total": 51,
    "source_files_scanned": 9,
    "lines_of_code": 772,
    "languages": {
      ".png": 17,
      ".py": 11,
      "(none)": 5,
      ".md": 5,
      ".gz": 4,
      ".yaml": 2,
      ".gif": 2,
      ".txt": 1,
      ".html": 1,
      ".js": 1,
      ".css": 1,
      ".json": 1
    }
  },
  "licence": {
    "spdx": "MIT",
    "class": "A",
    "source_file": "LICENSE",
    "redistribution_allowed": true
  },
  "dependencies": {
    "count": 0,
    "unique": 0,
    "by_ecosystem": {},
    "list": []
  },
  "owasp_top10": {
    "total_findings": 1,
    "files_with_findings": 1,
    "severity": {
      "high": 1,
      "medium": 0,
      "low": 0
    },
    "categories": {
      "A01-BrokenAccessControl": {
        "count": 0,
        "findings": []
      },
      "A02-CryptographicFailures": {
        "count": 0,
        "findings": []
      },
      "A03-Injection": {
        "count": 1,
        "findings": [
          {
            "severity": "high",
            "file": "utils/helper.py",
            "line": 29,
            "cwe": "CWE-78",
            "snippet": "shell=True,"
          }
        ]
      },
      "A04-InsecureDesign": {
        "count": 0,
        "findings": []
      },
      "A05-SecurityMisconfiguration": {
        "count": 0,
        "findings": []
      },
      "A06-VulnerableComponents": {
        "count": 0,
        "findings": []
      },
      "A07-AuthFailures": {
        "count": 0,
        "findings": []
      },
      "A08-SoftwareDataIntegrity": {
        "count": 0,
        "findings": []
      },
      "A09-LoggingMonitoringFailures": {
        "count": 0,
        "findings": []
      },
      "A10-SSRF": {
        "count": 0,
        "findings": []
      }
    }
  },
  "owasp_llm_top10": {
    "total_findings": 0,
    "files_with_findings": 0,
    "severity": {
      "high": 0,
      "medium": 0,
      "low": 0
    },
    "categories": {
      "LLM01-PromptInjection": {
        "count": 0,
        "findings": []
      },
      "LLM02-SensitiveInfoDisclosure": {
        "count": 0,
        "findings": []
      },
      "LLM03-SupplyChain": {
        "count": 0,
        "findings": []
      },
      "LLM04-DataPoisoning": {
        "count": 0,
        "findings": []
      },
      "LLM05-ImproperOutputHandling": {
        "count": 0,
        "findings": []
      },
      "LLM06-ExcessiveAgency": {
        "count": 0,
        "findings": []
      },
      "LLM07-SystemPromptLeak": {
        "count"
```
