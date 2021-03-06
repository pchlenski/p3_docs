Antibiotic Resistance
======================

.. raw:: html

  <div class="dlp">
    <h1>Antimicrobial Resistance (AMR)</h1>
    <section class="main">
    
      <!-- Section: Data -->
      <div class="data-tab" id="tab1">
        <h3></h3>
        <div class='large'>		
            <p>Antibiotics are a type of drugs used in the treatment and prevention of bacterial infections.
            Antimicrobial Resistance (AMR) refers to the ability of bacteria to resist the effects of antibiotics 
            that are commonly used to treat them. Resistance arises through one of three ways: natural resistance 
            in certain types of bacteria, genetic mutation, or by one species acquiring resistance from another. 
            PATRIC provides a variety of data and analysis tools to help researchers study AMR and its genetic determinants.       
            This includes AMR phenotype data for the bacterial genomes as well as genes and intergenic regions associated with AMR.
            </p>
        </div>

        <!-- Section: What do we mean by -->
        <div class="data-box" id="dlp-features-data">
          <h3 class="ribbon-title">What do we mean by ...</h3>
          <br/>
          <div class="data-box-lg">
              <h4>Antibiotics:</h4>
              <p>Antibiotics are a type of antimicrobial drugs used in the treatment and prevention of bacterial infections. 
              PATRIC provides basic information about commonly 
              used antibiotics, inlcuding their chemical and physical properties, pharmacology, and mechanism of action. 
              In addition, each antibiotic is linked to other relevant data available in PATRIC, such as
              AMR phenotypes for genomes, AMR genes, and AMR regions. Below are some examples: </p>
              <ul>
                  <li><a href="/view/Antibiotic/?eq(antibiotic_name,amikacin)">amikacin</a></li>
                  <li><a href="/view/Antibiotic/?eq(antibiotic_name,ethambutol)">ethambutol</a></li>
                  <li><a href="/view/Antibiotic/?eq(antibiotic_name,isoniazid)">isoniazid</a></li>
                  <li><a href="/view/Antibiotic/?eq(antibiotic_name,rifampoin)">rifampoin</a></li>
                  <li><a href="/view/Antibiotic/?eq(antibiotic_name,streptomycin)">streptomycin</a></li>
              </ul>
              <a href="/view/AntibioticList/?keyword(*)">View all antibiotics</a>
          </div>
          <div class="data-box-lg">
              <h4>AMR Phenotypes:</h4>
              <p>AMR phenotypes refer to the resistance or susceptibility of a given organism to one or more antibiotics. 
              PATRIC collects AMR phenotype data generated using antimicrobial susceptibility testing methods (AST) 
              from published studies and collaborators. In addition, we also provide predicted AMR phenotypes using 
              machine learning classifiers. See AMR phenotype data for select genera: </p>
              <ul>
                  <li><a href="/view/Taxonomy/1763#view_tab=amr">Mycobacterium</a></li>
                  <li><a href="/view/Taxonomy/1279#view_tab=amr">Staphylococcus</a></li>
                  <li><a href="/view/Taxonomy/1301#view_tab=amr">Streptococcus</a></li>
                  <li><a href="/view/Taxonomy/469#view_tab=amr">Acinetobacter</a></li>
                  <li><a href="/view/Taxonomy/286#view_tab=amr">Pseudomonas</a></li>
              </ul>
              <a href="/view/Taxonomy/2#view_tab=amr">View all AMR phenotype data</a>
          </div>
          <div class="data-box-lg">
              <h4>AMR Genes:</h4>
              <p>AMR genes refere to the genes implicated in or associated with the resistance to one or more antibiotics. 
              The resistance may result from the presence or absense of a gene or specific murations acquired sponteniously 
              or through evolution over time. We integrate and map known antibiotic resistance genes from the following sources:</p>
              <ul>
                  <li><a href="/view/Taxonomy/2#view_tab=specialtyGenes&filter=and(eq(property,%22Antibiotic%20Resistance%22),eq(source,%22ARDB%22))">ARDB</a></li>
                  <li><a href="/view/Taxonomy/2#view_tab=specialtyGenes&filter=and(eq(property,%22Antibiotic%20Resistance%22),eq(source,%22CARD%22))">CARD</a></li>
                  <li><a href="/view/Taxonomy/2#view_tab=specialtyGenes&filter=and(eq(property,%22Antibiotic%20Resistance%22),eq(source,%22NDARO%22))">NDARO</a></li>
                  <li><a href="/view/Taxonomy/2#view_tab=specialtyGenes&filter=and(eq(property,%22Antibiotic%20Resistance%22),eq(source,%22PATRIC%22))">PATRIC AMR</a></li>
              </ul>
              <a href="/view/Taxonomy/2#view_tab=specialtyGenes&filter=eq(property,%22Antibiotic%20Resistance%22)">View all AMR genes</a>
          </div>
          <div class="data-box-lg">
              <h4>AMR Regions:</h4>
              <p>AMR regions refer to the small genomic regions implicated in or associated with the resistance to one or more antibiotics.
              The AMR regions are computationally predicted using machine learning classifiers used to predict AMR phenotypes. They may map 
              to existing genes or intergenic regions and may help identify new AMR genes or understand AMR mechanisms.   
              </p>
              <a href="/view/FeatureList/?eq(feature_type,classifier_predicted_region)#view_tab=features&filter=or(eq(annotation,%22PATRIC%22))">View all AMR regions</a>
          </div>
          <div class="clear"></div>
        </div>

        <!-- popular genomes -->
        <div class="data-box popular-box tabbed hover-tabs no-underline-links">
          <h3 class="ribbon-title">Select Genomes</h3>
          <div class="group"></div>
        </div>
      </div>

      <!-- Section: Tools -->

      <!-- Section: Process -->
      <div class="data-tab" id="tab3">
        <div class="data-box">
          <h3 class="ribbon-title">How Do We Curate, Integrate, and Map Antibiotic Resistance Data?</h3>
            <img alt="How Do We Curate, Integrate, and Map Antibiotic Resistance Data?" src="http://docs.patricbrc.org/_static/website/data_landing_pages/antibiotics_resistance.jpg" />
        </div>
      </div>

      <!-- Section: Download -->
    </section>
  </div>

