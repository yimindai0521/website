---
authors:
  - admin
  - Ying Yan
publication_short: ""
abstract: In the past decade, various exact balancing-based weighting methods
  were introduced to the causal inference literature. Exact balancing alleviates
  the extreme weight and model misspecification issues that may incur when one
  implements inverse probability weighting. It eliminates covariate imbalance by
  imposing balancing constraints in an optimization problem. The optimization
  problem can nevertheless be infeasible when there is bad overlap between the
  covariate distributions in the treated and control groups or when the
  covariates are high-dimensional. Recently, approximate balancing was proposed
  as an alternative balancing framework, which resolves the feasibility issue by
  using inequality moment constraints instead. However, it can be difficult to
  select the threshold parameters when the number of constraints is large.
  Moreover, moment constraints may not fully capture the discrepancy of
  covariate distributions. In this paper, we propose Mahalanobis balancing,
  which approximately balances covariate distributions from a multivariate
  perspective. We use a quadratic constraint to control overall imbalance with a
  single threshold parameter, which can be tuned by a simple selection
  procedure. We show that the dual problem of Mahalanobis balancing is an l_2
  norm-based regularized regression problem, and establish interesting
  connection to propensity score models. We further generalize Mahalanobis
  balancing to the high-dimensional scenario. We derive asymptotic properties
  and make extensive comparisons with existing balancing methods in the
  numerical studies.
tags: []
slides: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "3"
summary: ""
url_dataset: "#"
url_project: ""
url_source: "#"
url_video: "#"
publication: ""
featured: false
date: 2019-04-07T00:00:00Z
url_slides: ""
title: "Mahalanobis balancing: a multivariate perspective on approximate
  covariate balancing"
links:
  - name: Custom Link
    url: http://example.org
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2017-01-01T00:00:00Z
url_poster: "#"
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
doi: ""
---
R package available in [MBalance.](https://github.com/yimindai0521/MBalance)