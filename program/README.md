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
            cursor: pointer;
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
/* Poster Modal styling */
#posterModal {
  display: none;
  position: fixed;
  z-index: 9999;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.4);
  justify-content: center;
  align-items: center;
}
#posterModalTitle {
    margin-top: 0;
    font-size: 20px;
    color: #737CBB;
}
#posterList {
      font-size: 16px;
      margin-top: 0;
}
#modalPosterButton span {
    padding: 6px 12px;
    margin-top: 10px;
    background-color: #B2B9E8;
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
        <tr><td>08:00-08:30</td><td>Registration & Coffee</td><td rowspan="2" colspan="2">Tea</td></tr>
        <tr><td>08:30-08:50</td><td rowspan="2">Welcome</td></tr>
        <tr><td>08:50-09:00</td><td colspan="2">Welcome</td></tr>
        <tr>
            <td>09:00-09:40</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 1: Impact of biometrics in public and private breeding programs', '9-9:40: Gary Atlin, Bill & Melinda Gates Foundation', 'Early-stage sparse testing can increase selection accuracy and genetic gain in plant breeding programs',
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
                <div class="embed_container" onclick="openModal('Session 8: Artificial Intelligence and machine learning in practice', '11:10-11:50: Julian Taylor, University of Adelaide', 'Integrating artificial intelligence and machine learning capability into Australian grains agriculture',
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
        <tr><td>12:50-13:20</td><td class="break"  rowspan="2">Lunch (1 hour)</td><td class="break">Packed lunch supplied before social events</td><td class="break"  rowspan="2">Lunch  (1 hour)</td></tr>
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
                <div class="embed_container" rowspan="3" onclick="openModal('Session 9: Managing genetic diversity and maximising long-term genetic gains', '13:50-14:30: Keith Gardner, CIMMYT', 'Effective and Efficient Utilization of Gene Bank Resources using Quantitative Genetics',
                '14:30-14:45: Carolina Rivera-Poulsen', 'A rapid cycling genomic selection experiment in maize landraces',
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
              <div class="poster_container" onclick="openPosterModal('Poster Session 2', [
                    {title:'For greener whisky: barley’s genetic control for agronomic and metabolic adaptation to reduced nitrogen fertilizer inputs', author:'George Terry Epaku'},
                    {title:'Rare Genetic Variation Underlies Extremely Low Trigonelline Levels in Maize Grain',author:'Michael Gore'},
                    {title:'TAdvancing Genomic Selection in Grapevine: Development and Analysis of a Training Population',author:'Valeria De Rosa'},
                    {title:'Uncovering Genomic Regions Controlling Root Quality Traits in Cassava implementing various GWAS models',author:'Diana Carolina Solarte Certuche'},
                    {title:'Genetic analysis of a short-term selection experiment with Saccharina latissima: lessons learned',author:'Signe Bråtelund'},
                    {title:'Combining ability of banana triploid hybrid progenitors and genomic prediction for agro-morphological traits',author:'Lucile Toniutti'},
                    {title:'Combining ecophysiological and genetic modeling to identify new breeding targets for water stress tolerance in tomato',author:'Fabien Tirado'},
                    {title:'First Application of Genomic Prediction in Quinoa',author:'Clara Stanschewski'},
                    {title:'Neodomestication of a halophytic perennial grain (Distichlis palmeri)',author:'Izamar Olivas Orduna'},
                    {title:'Genome-wide insights into wheat flour properties and rheology: Genetic markers and candidate genes for improving end-use quality',author:'Juan Menor de Gaspar'},
                    {title:'Quantifying Protein Levels in Cereal–Legume Intercrops Using Near-Infrared Spectroscopy',author:'Reena Dubey'},
                    {title:'Genetic evaluation and simulation of grain yield in Australia Southern faba bean breeding program',author:'Huanhuan Zhao'},
                    {title:'Dissecting the Genetic Basis of Cold Tolerance in Potato through QTL Mapping and Functional Analysis of CBF1',author:'Beiyu Tu'},
                    {title:'flexFitR and exploreHTP: Open-source software to enable nonlinear modeling of plant growth from remotely-sensed imagery',author:'Johan Steven Aparicio'},
                    {title:'Haplotype stacking to improve stability of stripe rust resistance in wheat',author:'Jingyang Tong'},
                    {title:'Harnessing Plant Genetic Resources without compromising local adaptation in hybrid and inbred wheat breeding programs',author:'Maegan Green'},
                    {title:'Dissecting Genotype × Environment Interactions for Cold Tolerance Traits in Sorghum Using a Haplotype-Based Framework',author:'Mohamed Mosalam'},
                    {title:'Leveraging a broad gradient of plant-plant interactions to efficiently breed for cereale-legume mixtures',author:'Jemay Salomon'},
                    {title:'Harnessing Heterosis in Faba Bean: Breeding strategy optimisation through stochastic simulations',author:'Amanda Karlström'},
                    {title:'Enhancing QTL Detection and Genomic Prediction for Stay-Green in Maize Using UAV-Based Multi-Trait Analysis',author:'Yan-Cheng Lin'},
                    {title:'Discovering Optimal Genotype–Environment combinations in Rice Through a Bayesian Optimization-like Random Forests',author:'Hideto Mochizuki'},
                    {title:'Identification of maize heterotic group-specific haplotypes and impact of residual inbreeding on elite hybrids grain yield',author:'Romain Kadoumi'},
                    {title:'Joint analysis of monovarietal and mixed stand performances to study the genetic architecture of indirect genetic effects in wheat cutltivar mixtures',author:'Maxence Remerand'},
                    {title:'EasyGeSe – A resource for benchmarking genomic prediction methods',author:'Daniel Ariza-Suarez'},
                    {title:'Can We Teach Machines to Select Like a Plant Breeder? A Recommender System Approach to Support Early Generation Selection Decisions Based on Breeders\’ Preferences',author:'Sebastian Michel'},
                    {title:'Quantifying the Drivers of Genetic Change in Plant Breeding',author:'Thiago de Paula Oliveira'},
                    {title:'CrossingTools: An R Package for Mating Optimization in Plant Breeding',author:'Sven Weber'},
                    {title:'AI-based predictions in canola',author:'Iulian Gabur'},
                    {title:'Identification of QTL involved in heavy metal and trace element accumulation in durum wheat',author:'Alexia Crézé'},
                    {title:'Insufficient memory: a practical problem associated with the genomic relationship matrix and estimation of GxE effects for grain yield across multiple years and sites',author:'Wallace Cowling'},
                    {title:'Integration of environmental predictors and genomic selection into a pipeline for global potato variety recommendation',author:'Marco Peixoto'},
                    {title:'PredictPro: An Integrated Analytics Pipeline for Multi-Omics Machine Learning and AI-Based Prediction in Plant Breeding',author:'Sikiru Adeniyi Atanda'},
              ])">
                <div class="poster_item">Farewell Reception & Poster Session 2</div>
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
        <div class="poster_container" onclick="openPosterModal('Poster Session 1', [
              {title:'Disentangling the genetic and environmental factors influencing GxE for barley yield', author:'Stephanie Brunner'},
              {title:'AI-Driven Analysis of Big Biological Data to Decode Genotype-Environment Interaction', author:'Huihui Li'},
              {title:'From light to biomass: using dynamic photosynthesis data to improve biomass predictions', author:'Junita Solin'},
              {title:'Elucidating the genetic architecture of heterosis in Central European wheat', author:'Guoliang Li'},
              {title:'Ideas and recommendations for optimal field experimental designs in artificial selection programs', author:'Giovanny Covarrubias-Pazaran'},
              {title:'Using phenomic selection to predict hybrid values of parental lines in nurseries – Proof of concept on maize', author:'Renaud Rincent'},
              {title:'Genomic and Phenomic Prediction Performance for Tree Architecture and Fruit Quality Traits in Apple',author:'Nuri Güvencli'},
              {title:'Increasing nitrogen use efficiency of winter oilseed rape (Brassica napus L.) by improving genetics and cultivation system interaction',author:'Daniel Valle Torres'},
              {title:'Quality over Quantity? The optimized allocation of quality samples of perennial ryegrass in Bavarian state cultivar trials',author:'Anne-Katrin Gorn'},
              {title:'Breeding for Maize Varieties with Reduced Carbon Footprints',author:'Kathryn Grant'},
              {title:'Leveraging Disentangled Representations to Predict Unobserved Genotype-Environment Combinations in Phenomic Selection',author:'Tristan Mary-Huard'},
              {title:'Disentangling the genetic response to seasonal and environmental drivers',author:'Katharine Preedy'},
              {title:'Introducing the 2NP matrix in genomic prediction: A novel genomic matrix that merges the strengths of classical and machine learning methods in plant breeding',author:'Bright Enogieru Osatohanmwen'},
              {title:'Sparse testcrossing for early-stage genomic prediction of general combining ability to increase genetic gain in maize hybrid breeding programs',author:'David González-Diéguez'},
              {title:'Harnessing Genetic Diversity from the Wider Cultivated Gene Pool to Advance Trait Analysis and Breeding in Potato',author:'Sanjeev Kumar Sharma'},
              {title:'Study of the impact of genome editing in a perennial species breeding program through simulations',author:'Xabi Cazenave'},
              {title:'Robustness Evaluation of Machine Learning Models in Genomic Prediction',author:'Vanda Lourenço'},
              {title:'Types of Plant Breeding Paper',author:'Rex Bernardo'},
              {title:'Co-Evolutionary Analysis for Mining Functional Genes from Plant Genomes',author:'Shang Gao'},
              {title:'Identifying Stable and High-Yielding Oil Palm Genotypes in a Long-Term Single-Site Breeding Trial',author:'Mohd Ibnur Syawal Zakaria'},
              {title:'Barley Breeding Under Long Days: Reducing Speed Breeding Energy Use and Unlocking Flowering Plasticity for Climate Resilience',author:'Nicola Rossi'},
              {title:'An interpretable machine learning-based alternative to genome-wide association studies (GWAS), and its application in a wild population',author:'Gard Gravdal'},
              {title:'The Impact of Increased Recombination on Breeding Programs: Insights from Simulations',author:'Boyny Zsa Zsa'},
              {title:'Permutation-based GWAS in raspberry',author:'Philip Greenspoon'},
              {title:'Building Foundations for \'Ensembl Plant Populations\'',author:'James Bedford'},
              {title:'Predicting Novel Genotypes in Untested Environments Using Large Multi-Environment Datasets Across Species',author:'Vincent Garin'},
              {title:'Strategic Crossing to improve genetic potential in soybean breeding',author:'Kengo Sakurai'},
              {title:'Genome-wide association study of agronomical and nutritional traits in oat using a recurrent selection population with Avena sterilis introgressions',author:'Kai Ilves'},
              {title:'Genotype-by-Environment interactions in Norwegian Barley: insights from a decade of multi-location trials',author:'Min Lin'},
              {title:'IMPROVING GENOMIC PREDICTION IN WHEAT WITH RANDOM REGRESSION MODELS  FOR ENVIRONMENTAL COVARIATES',author:'Rishap Dhakal'},
              {title:'QTL Mapping and Candidate Genes Associated with Common Bean Resistance to Root-Knot Nematode (Meloidogyne incognita)',author:'Antonio Augusto Franco Garcia'},
              {title:'Implementation of genomic selection in Miscanthus sinensis for ecosystem services',author:'Séverine Monnot'},
              {title:'Maximizing G×E Value in Forestry Breeding Using a Three-Stage Approach',author:'Mason Chizk'},
              {title:'From Fields to Fjords: A framework for targeting resilience by simulating longitudinal growth traits in plants and aquaculture',author:'Duncan Henderson'},
              {title:'Genotype and Phenotype Encryption Optimised for Federated Quantitative Genetics',author:'Richard Mott'},
              {title:'Comparing uni-modal vs multi-modal ML modeling of GxE interactions on hybrid maize data',author:'Finn Gaida'},
        ])">
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
<!-- Poster Modal -->
<div id="posterModal" style="display:none; position:fixed; z-index:9999; left:60px; top:0; width:100%; height:100%; background:rgba(0,0,0,0.4); justify-content:center; align-items:center;">
  <div style="background:white; padding:20px; border-radius:10px; max-width:650px; max-height:80%; overflow-y:auto;">
    <h2 id="posterModalTitle">Poster Session</h2>
    <ol id="posterList" style="font-size:16px; line-height:1.6;"></ol>
    <div id="modalPosterButton">
      <span onclick="closePosterModal()" 
        style="display:inline-block; margin-top:10px; padding:6px 12px; background:#ccc; color:white; border-radius:4px; cursor:pointer;"
            onmouseover="this.style.background='#999'; this.style.color='white';"
            onmouseout="this.style.background='#B2B9E8'; this.style.color='white';">
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
  
  function openPosterModal(title, posters) {
  document.getElementById('posterModalTitle').innerText = title;
  let start;
  if (title == "Poster Session 1") {
        start = 1;
    } else {
        start = 37;
    }
  let list = document.getElementById('posterList');
  list.innerHTML = "";
  posters.forEach((p, i) => {
  let li = document.createElement("li");
  li.style.listStyleType = "none";
  li.innerHTML = `<div style="text-indent:-20px;">${i+start}. <strong>${p.author}</strong>: ${p.title}</div>`;
  list.appendChild(li);
  });
  document.getElementById('posterModal').style.display = 'flex';
}

function closePosterModal() {
    document.getElementById("posterModal").style.display = "none";
  }
window.onclick = function(event) {
    const modal = document.getElementById('modal');
    const posterModal = document.getElementById('posterModal');
    if (event.target == modal) {
        modal.style.display = "none";
    }
    if (event.target == posterModal) {
        posterModal.style.display = "none";
    }
}
</script>


