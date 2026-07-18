NSF SBIR Phase I LaTeX Templates

Place these files under:
sections/main/

Core narrative:
4_Project_Summary.tex
5_Project_Description.tex
6_References_Cited.tex

System worksheets:
1_Cover_Sheet_Worksheet.tex
2_SBIR_Phase_I_Questionnaire_Worksheet.tex
3_SBIR_Phase_I_Certification_Worksheet.tex

Budget:
7_Budget.tex
8_Budget_Justification.tex

Supporting:
9_Facilities_Equipment_Other_Resources.tex
10_Senior_Key_Personnel_Documents_Tracker.tex
10A_Synergistic_Activities_Template.tex
11_Data_Management_Sharing_Plan.tex
12_Mentoring_Plan_Conditional.tex
13_Other_Personnel_Biographical_Information.tex

Supplementary:
14A_Company_Commercialization_History_Conditional.tex
14B_Consultant_Subaward_Commitment_Template.tex
14C_Resubmission_Change_Description_Conditional.tex
14D_Letter_of_Support_Template.tex
14E_IP_Rights_Agreement_Conditional.tex
14F_Other_Personnel_Biographical_Information.tex

Files marked Conditional should only be used when applicable.


======================================================
VibeFab NSF SBIR Phase I - ShareLaTeX/Overleaf Package
4_Project_Summary_5_Project_Description_6_References.tex
======================================================

Files
-----
4_Project_Summary_5_Project_Description_6_References.tex
    - project_summary
        --  One-page Project Summary with the required standalone headings:
            Overview, Intellectual Merit, and Broader Impacts.

    - project_description
        -- Fifteen-page Phase I Project Description.
        -- Required top-level headings are used exactly:
            Intellectual Merits, Company/Team, Broader Impacts, and Commercialization Potential.
        -- All figures and tables are generated in LaTeX; there are no external image dependencies.

    - references_cited
        -- Separate References Cited upload.

references.bib
    - BibLaTeX database shared by the Project Description and References Cited files.

proposal_style.tex
    - Shared formatting and package configuration.

Overleaf compilation
--------------------
Set the compiler to pdfLaTeX.

The bibliography backend is Biber. Overleaf normally runs Biber automatically. If citations do not appear, use “Recompile from scratch.”

Required factual and budget verification before submission
-----------------------------------------------------------
The narrative is complete and contains no visible placeholders, but the company must verify that the following statements match official records and the final budget:

1. ALTITUT LLC organization date: May 16, 2026.
2. Revenue, direct government-funding, and private-investment statements.
3. Customer evidence: 53 discovery conversations, more than 1,000 learners, dozens of deployments, and more than 40 educators.
4. Austin Community College’s approved role and support-letter language.
5. Personnel effort: PI 3.0 person-months; Key Personnel 2.0; software/AI personnel 4.0; independent EE reviewer 1.0.
6. The independent EE reviewer must be named or budgeted consistently if retained in the final proposal.
7. Planned benchmark size (120 cases), participant walkthrough sample (12-18), three prototypes, and available laboratory equipment.
8. Working license-price and market assumptions; these are explicitly framed as Phase I hypotheses but must remain consistent with the Commercialization Potential section and budget.
9. All publication authors, titles, years, and DOI information in references.bib.
10. Project title and LC4 subtopic selection on the Research.gov Cover Sheet.


REFERENCE UPDATE (July 2026)
- References Cited expanded from 26 to 45 entries.
- Intellectual Merits Sections 1.1-1.9 now cite 40 unique sources.
- Added 19 recent 2023-2024 peer-reviewed/high-impact sources from Nature, TACL, TMLR, ICLR, NeurIPS, ICML, CVPR, EMNLP, ACM TODAES, IEEE TCAD, Computers & Education: Artificial Intelligence, and International Journal of Educational Technology in Higher Education.
- Before submission, verify final bibliographic metadata in your institution's database and remove any source that is not directly used in the final narrative.

REFERENCE UPDATE (July 2026)
- Expanded bibliography to 51 total references.
- Includes 40 research journal/conference papers dated 2023-2026, plus authoritative reports, prior team work, and named commercial documentation.
- Every bibliography entry is cited in the Project Description.
- Citations were strengthened throughout Sections 1.1-1.9, including uncertainty calibration, external verification, multimodal/document reasoning, EDA/hardware generation, physical feedback, education adoption, and responsible deployment.
