---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: News
    content:
      title: News
      text: |-
        - <2024-11> One paper accepted to [NDSS 25](https://www.ndss-symposium.org/ndss2025/).
        - <2024-09> One paper accepted to [Oakland 2025](https://sp2025.ieee-security.org/cfpapers.html).
        - <2024-08> One paper accepted to [CCS 2024](https://www.sigsac.org/ccs/CCS2024/).
        - <2024-07-16 Tue> I joined HKU as a postdoctoral researcher.
        - <2024-05-14 Tue> I passed my Ph.D. defense at CUHK.
      filters:
        folders:
          - newss
    design:
      columns: '2'
      view: compact
  - block: collection
    id: Publications
    content:
      title: Publications
      text: |-

        * Denotes the Corresponding Author.

        - **Predator: Directed Web Application Fuzzing for Efficient Vulnerability Validation**.

          Chenlin Wang, Wei Meng, <u>Changhua Luo</u>, and Penghui Li.

          To appear in Proceedings of The 46th IEEE Symposium on Security and Privacy (Oakland), May 2025.

        - **Automatic Library Fuzzing through API Relation Evolvement**.

          Jiayi Lin, Qingyu Zhang, Junzhe Li, Chenxin Sun, <u>Changhua Luo</u>*, Hao Zhou, and Chenxiong Qian*.

          To appear in Proceedings of The 32nd Annual Network and Distributed System Security Symposium (NDSS), Feb 2025.

        - **Test Suites Guided Vulnerability Validation for Node.js Applications**. [[PDF]](papers/ccs24_jsgo.pdf)[[code]](https://github.com/WHU-seclab/JSGo)

          <u>Changhua Luo</u>, Penghui Li, Wei Meng, Chao Zhang. 

          In Proceedings of The 31st ACM Conference on Computer and Communications Security (CCS), Oct 2024.

        - **Holistic Concolic Execution for Dynamic Web Applications via Symbolic Interpreter Analysis**. [[PDF]](papers/sp24_sia.pdf)[[code]](https://github.com/secureweb/symphp)

          Penghui Li, Wei Meng, Mingxue Zhang, Chenlin Wang, <u>Changhua Luo</u>. 

          In Proceedings of The 45th IEEE Symposium on Security and Privacy (Oakland), May 2024.

        - **Strengthening Supply Chain Security with Fine-grained Safe Patch Identification**. [[PDF]](papers/icse24_spatch.pdf)[[code]](https://github.com/cuhk-seclab/SPatch)

          <u>Changhua Luo</u>, Wei Meng, Shuai Wang. 

          In Proceedings of 46th International Conference on Software Engineering (ICSE), research track, April 2024.

        - **SelectFuzz: Efficient Directed Fuzzing with Selective Path Exploration**. [[PDF]](papers/sp23_selectfuzz.pdf)[[code]](https://github.com/cuhk-seclab/SelectFuzz)

          <u>Changhua Luo</u>, Wei Meng, Penghui Li.

          In Proceedings of The 44th IEEE Symposium on Security and Privacy (Oakland), May 2023.

        - **TChecker: Precise Static Inter-Procedural Analysis for Detecting Taint-Style Vulnerabilities in PHP Applications**. [[PDF]](papers/ccs22_tchecker.pdf)[[code]](https://github.com/cuhk-seclab/TChecker)

          <u>Changhua Luo</u>, Penghui Li, Wei Meng. 

          In Proceedings of The 29th ACM Conference on Computer and Communications Security (CCS), Nov 2022.

          <span style="color: red;">&#9733; ACM CCS 2022 Best Paper Honorable Mention, 20/971=2.06%.</span>

        - **On the Feasibility of Automated Built-in Function Modeling for PHP Symbolic Execution**. [[PDF]](papers/www21_xsym.pdf)[[code]](https://github.com/cuhk-seclab/xsym)

          Penghui Li, Wei Meng, Kangjie Lu, <u>Changhua Luo</u>. 

          In Proceedings of the 30th Web Conference (WWW), security track, Feb 2021.
      filters:
        folders:
          - publications
    design:
      columns: '2'
  - block: collection
    id: Services
    content:
      title: Services
      text: |-
        **Technical Program Committee**
        - IEEE International Conference on Parallel and Distributed Systems (ICPADS), 2024

        **External Reviewer**
        - IEEE Symposium on Security and Privacy (Oakland), 2023, 2024
        - The ACM Conference on Computer and Communications Security (CCS), 2021, 2022, 2023, 2024
        - The Web Conference (WWW), 2020, 2021, 2022, 2024
        - The ACM ASIA Conference on Computer and Communications Security (ASIACCS), 2021, 2022
      filters:
        folders:
          - services1
    design:
      columns: '2'
---
