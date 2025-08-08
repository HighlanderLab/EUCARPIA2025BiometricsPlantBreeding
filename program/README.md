
# Scientific program
There will be nine session as shown below. We envisage that each session will have one plenary and four contributed talks.
💡 Tip: Click on each session title to view the full session programme and details.
<style>
      table {
            width: 100%;
            max-width: 1200px;
            border-collapse: collapse;
            margin: 20px 100px;
            padding: 0;
            background-color:rgba(244, 244, 244, 0);
            box-shadow: 0 0px 0px rgba(0, 0, 0, 0.2);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        th {
            color:rgb(20, 19, 21);
            font-size: 18px;
        }
        .session {
            color: #4a148c;
        }
        .break {
            color: #1a237e;
        }
        .social {
            font-weight: bold;
            color:rgb(17, 18, 80);
        }
        .embed_container {
            display: flex;
            flex-direction: column;
            align-items: center;
            background:rgba(203, 173, 216, 0.7);
            padding: 10px;
            margin-top: 5px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            position: relative;
        }
        .embed_title {
            flex-direction: column;
            margin-bottom: 0px;
            margin-top: -10px;
            background:rgb(143, 94, 163);
            color: white;
            padding: 5px 10px;
            border-radius: 8px;
            white-space: normal;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            font-size: 14px;
            text-align: center; 
            line-height: 1.4; 
            font-weight: bold;
            width: 110%;
        }
        .embed_item {
            margin: 5px 0;
            font-size: 14px;
            /* font-weight: bold; */
        }
        .poster_container {
            display: flex;
            flex-direction: column;
            align-items: center;
            background:rgba(178, 185, 232, 0.7);
            padding: 10px;
            margin-top: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        .poster_title {
            margin-bottom: 5px;
            background:rgb(80, 92, 170);
            color: white;
            padding: 2px 15px;
            border-radius: 10px;
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            white-space: nowrap;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        .poster_item {
            margin: 5px 0;
            font-weight: bold;
        }
        @media (max-width: 600px) {
            table {
                font-size: 14px;
            }
        }
/* Modal styling */
  #modal {
    display: none;
    position: fixed;
    z-index: 9999;
    left: 60px; top: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.4);
    justify-content: center;
    align-items: center;
  }
  #modalContent {
    background: white;
    padding: 20px;
    border-radius: 10px;
    min-width: 300px;
    max-width: 650px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    text-align: left;
  }
  #modalContent h2 {
    margin-top: 0;
    font-size: 20px;
    color: #4a148c;
  }
  #modalContent h3 {
    font-size: 16px;
    margin: 10px 0;
    color: #4a148c;
  }
  #modalContent p {
    font-size: 16px;
    margin: 10px 0;
  }
  #modalButton span {
    padding: 6px 12px;
    margin-top: 10px;
    background-color: #4a148c;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
</style>

<table>
        <tr>
            <th style="width: 200px;">Time</th>
            <th style="width: 300px;">Wednesday</th>
            <th style="width: 300px;">Thursday</th>
            <th style="width: 300px;">Friday</th>
        </tr>
        <tr><td>08:00-08:30</td><td>Registration</td><td rowspan="2" colspan="2"></td></tr>
        <tr><td>08:30-08:50</td><td rowspan="2">Welcome</td></tr>
        <tr><td>08:50-09:00</td><td colspan="2">Welcome</td></tr>
        <tr>
            <td>09:00-09:40</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 1: Impact of biometrics in public and private breeding programs', '9-9:40: Gary Ailin, Bill & Melinda Gates Foundation', 'Early-stage sparse testing can increase selection accuracy and genetic gain in plant breeding programs',
                '9:40-9:55: Christian Werner', 'Reviving the Desired Gains Index: an optimal solution for parent selection in plant breeding programmes',
                '9:55-10:10: Wubishet Bekele ', 'Lessons from a Decade of Streamlining Genomic Selection in Oat Breeding Programs at AAFC',
                '10:10-10:25: Augustin Desprez', 'Twenty years of asymmetrical hybrid breeding drives diversity and targets domestication genes in commercial elite sugar beet inbreds',
                '10:25-10:40: Leticia Lara ', 'Trait prioritization and economic modelling to guide strategic decisions in pea breeding program')">
                    <div class="embed_title">Gary Atlin</div>
                    <div class="embed_item">S1: Impact of biometrics in public and private breeding programs</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 5: Genotype performance, stability and resilience', '9-9:40: Andrea Wilson, University of Edinburgh', 'G x Infectious E: Breeding for reduced pathogen transmission',
                '9:40-9:55: Emilia Koch', 'A hurdle model for ordinal scoring data with an underlying percentage scale',
                '9:55-10:10: Lucia Gutierrez', 'How many environments do we really need for yield stability prediction in cereals',
                '10:10-10:25: Dominic Waters', 'The role of stability metrics in plant breeding programmes',
                '10:25-10:40: Hugo Dorado', 'Estimating genetic performance and variability on-farm using ranking data')">
                    <div class="embed_title" >Andrea Wilson</div>
                    <div class="embed_item">S5: Genotype performance, stability and resilience</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 7: High-throughput phenotyping', '9-9:40: María Xosé Rodríguez-Álvarez, University of Vigo', 'Spatio-Temporal Modelling of Genotypic Performance in High-Throughput Phenotyping',
                '9:40-9:55: Corné Verburg', 'Bridging Genomic Prediction and Crop Growth Modeling with System Identification for Nonlinear Dynamics (SINDy)',
                '9:55-10:10: Timothy Thavarajah', 'Deploying computer vision and bivariate genomic prediction to improve blackleg disease resistance in canola breeding',
                '10:10-10:25: Ángela Prudencio', 'Integration of new RFID-based pollinator parameters into plant phenotyping and breeding selection indexes under climate change pressure',
                '10:25-10:40: Clément Bienvenu', 'Optimizing GxE Prediction in Phenomic Selection Using Chemometric Decomposition of NIRS Data')">
                    <div class="embed_title" >María Xosé Rodríguez-Álvarez</div>
                    <div class="embed_item">S7: High-throughput phenotyping</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>09:40-10:10</td>
        </tr>
        <tr>
        <td>10:10-10:40</td>
        </tr>
        <tr><td>10:40-11:10</td><td class="break" colspan="3">Morning Tea (30 minutes)</td></tr>
         <tr>
            <td>11:10-11:50</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 2: Design of experiments and multi-environment trials', '11:10-11:50: Rosemary Bailey, University of St Andrews', 'Designs with more than one blocking system: the conflict between valid randomization and latinization',
                '11:50-12:05: Emi Tanaka', 'Leveraging large language models in a composable system to design and simulate plant experiments',
                '12:05-12:20: Karen Wolf', 'On Deficient Experimental Designs and Their Analysis',
                '12:20-12:35: Michaela Jung', 'Designing multi-environment reference populations in perennials: Do\'s and don\'ts',
                '12:35-12:50: Bjarne Nielsen', 'Power calculations for testing genetic correlation between pure- and mixture line effects in wheat breeding')">
                    <div class="embed_title">Rosemary Bailey</div>
                    <div class="embed_item">S2: Design of experiments and multi-environment trials</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 6: Modelling and leveraging genotype by environment interaction', '11:10-11:50: Steven Penfield, John Innes Centre', 'Exploiting genotype by environment interactions to breed for local adaptation and climate change resilience in winter rapeseed',
                '11:50-12:05: Shanice Van Haeften', 'Characterising Genotypic Stability and Environmental Responsiveness in Australian Chickpea',
                '12:05-12:20: Jip Ramakers', 'Multiple-covariate random regression for predicting yield across the Australian wheatbelt',
                '12:20-12:35: Killian Melsen', 'REML implementations of kernel-based multi-trait, multi-environment genomic prediction models',
                '12:35-12:50: Wera Eckhoff', 'Tailoring AI and ML Models for Genotype-by-Environment Prediction Leveraging Environmental Covariates: A European Rye Example')">
                    <div class="embed_title">Steven Penfield</div>
                    <div class="embed_item">S6: Modelling and leveraging genotype by environment interaction</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 8: Artificial Intelligence and machine learning in practice', '11:10-11:50: Julian Taylor, University of Adelaide', 'title of talk',
                '11:50-12:05: Tally Wright', 'Exploring Random Forest-based genomic prediction for optimised selection of reference barley varieties for inclusion in DUS distinctiveness evaluation',
                '12:05-12:20: Carles Quesada-Traver', 'Opportunities and limitations of deep learning-based multi-environment genomic prediction',
                '12:20-12:35: Sarah Ghysels', 'Image-based yield prediction for tall fescue using random forests and convolutional neural networks',
                '12:35-12:50: Natasha Johansen', 'Evolutionary-scale protein language models effectively uncover beneficial variants in a sorghum bicolor diversity panel')">
                    <div class="embed_title" >Julian Taylor</div>
                    <div class="embed_item">S8: Artificial Intelligence and machine learning in practice</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>11:50-12:20</td>
        </tr>
        <tr>
        <td>12:20-12:50</td>
        </tr>
        <tr><td>12:50-13:20</td><td class="break"  rowspan="2">Lunch (1 hour)</td><td class="break">Pick up lunch before social events</td><td class="break"  rowspan="2">Lunch  (1 hour)</td></tr>
        <tr><td>13:20-13:50</td><td class="break"  rowspan="9">
        <div>
        Social Program
        </div>
        </td></tr>
        <tr>
            <td>13:50-14:30</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 3: Genetic and genomic modelling of plant breeding data', '13:50-14:30: Pascal Schopp, KWS Group', 'A genomic selection reality check from industry: what moves the needle in genetic gain',
                '14:30-14:45: Yong Jiang ', 'An efficient and powerful algorithm for detecting heterotic QTL',
                '14:45-15:00: Tristan Mary-Huard', 'A Composite Hypothesis Testing Approach to Detect Pleiotropic Genomic Regions',
                '15:00-15:15: Antero Heikkilä ', 'Approximating prediction error variances of genomic models using Monte Carlo sampling',
                '15:15-15:30: Javier Fernández-González', 'Why REML variance estimates have no biological meaning and how to solve it')">
                    <div class="embed_title" >Pascal Schopp</div>
                    <div class="embed_item">S3: Genetic and genomic modelling of plant breeding data</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" rowspan="3" onclick="openModal('Session 9: Managing genetic diversity and maximising long-term genetic gains', '13:50-14:30: Keith Gardner, CIMMYT', 'title of talk',
                '14:30-14:45: Carolina Rivera-Poulsen', 'A rapid cycling selection experiment in maize landraces',
                '14:45-15:00: Kira Villiers', 'An algorithm for mate selection by haplotype stacking',
                '15:00-15:15: Sónia Surgy', 'The maximisation of the genetic gains of the polyclonal selection in grapevine varieties using integer programming',
                '15:15-15:30: Seifelden Metwally', 'A novel framework to control genetic diversity for optimal genomic mating')">
                    <div class="embed_title" >Keith Gardner</div>
                    <div class="embed_item">S9: Managing genetic diversity and maximising long-term genetic gains</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>14:30-15:00</td>
        </tr>
        <tr>
        <td>15:00-15:30</td>
        </tr>
        <tr><td>15:30-16:00</td>
              <td class="break">Afternoon Tea (30 mins)</td>
              <td class="break" rowspan="3">        
              <div class="poster_container">
                <div class="poster_item">Poster Session 2</div>
              </div>
              </td>
        </tr>
        <tr>
            <td>16:00-16:40</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 4: Innovative models with unconventional data streams', '16:00-16:40: Hao Cheng, UC Davis', 'Beyond Mixed Models: Integrative Models for Agricultural G2P Using Unconventional Data Streams',
                '16:40-16:55: Hannah Robinson', 'Leveraging Multi-Omics for Predictive Modelling in Perennial Crops: A Case Study in Grapevine',
                '16:55-17:10: Aiyesa Leke Victor', 'Genomic Prediction at the Root: From one plant to better populations',
                '17:10-17:25: Timothée Flutre', 'Quantifying the genetic basis of mixing ability and investigating its genetic architecture: case studies in wheat varietal mixtures and wheat-pea intercrops',
                '17:25-17:40: Nicolas Salas', 'When Durum Wheat grows together with Alfalfa: The Genetic Dialogue of Neighboring Plants')">
                    <div class="embed_title" >Hao Cheng</div>
                    <div class="embed_item">S4: Innovative models with unconventional data streams </div>
                </div>
            </td>
        </tr>
        <tr>
        <td>16:40-17:10</td>
        </tr>
        <tr>
        <td>17:10-17:40</td>
        <td class="break" rowspan="2">Conference Ends</td>
        </tr>
        <tr><td>17:40-</td>
        <td class="break">
        <div class="poster_container">
          <div class="poster_item">Drinks Reception & Poster Session 1</div>
        </div>
        </td>
        </tr>
    </table>

<!-- Modal -->
<div id="modal">
  <div id="modalContent">
    <h2 id="modalTitle">Title</h2>
    <h3 id="modalSubtitle0">talk 0</h3>
    <h3 id="modalDetails0" style="padding-left: 2em;font-weight: bold;">title of talk 0</h3>
    <p id="modalSubtitle1" style="font-weight: bold;">talk 1</p>
    <p id="modalDetails1" style="padding-left: 2em;">title of talk 1</p>
    <p id="modalSubtitle2" style="font-weight: bold;">talk 2</p>
    <p id="modalDetails2" style="padding-left: 2em;">title of talk 2</p>
    <p id="modalSubtitle3" style="font-weight: bold;">talk 3</p>
    <p id="modalDetails3" style="padding-left: 2em;">title of talk 3</p>
    <p id="modalSubtitle4" style="font-weight: bold;">talk 4</p>
    <p id="modalDetails4" style="padding-left: 2em;">title of talk 4</p>
    <div id="modalButton">
    <span onclick="closeModal()" 
      style="display:inline-block; margin-top:10px; padding:6px 12px; background:#ccc; border-radius:4px; cursor:pointer;"
      onmouseover="this.style.background='#999'; this.style.color='white';"
      onmouseout="this.style.background='#4a148c'; this.style.color='white';">
      Close
    </span>
    </div>
  </div>
</div>

<script>
  function openModal(title, subtitle0, details0,subtitle1, details1,subtitle2, details2,subtitle3, details3,subtitle4, details4) {
    document.getElementById('modalTitle').innerText = title;
    document.getElementById('modalSubtitle0').innerText = subtitle0;
    document.getElementById('modalDetails0').innerText = details0;
    document.getElementById('modalSubtitle1').innerText = subtitle1;
    document.getElementById('modalDetails1').innerText = details1;
    document.getElementById('modalSubtitle2').innerText = subtitle2;
    document.getElementById('modalDetails2').innerText = details2;
    document.getElementById('modalSubtitle3').innerText = subtitle3;
    document.getElementById('modalDetails3').innerText = details3;
    document.getElementById('modalSubtitle4').innerText = subtitle4;
    document.getElementById('modalDetails4').innerText = details4;
    document.getElementById('modal').style.display = 'flex';
  }

  function closeModal() {
    document.getElementById("modal").style.display = "none";
  }
</script>
