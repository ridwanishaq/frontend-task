<template>
   <!-- Page Content -->
  <div id="content">
    <div class="col-md-12 d-flex mb-3 w-arrow">
      <button class="btn btn-primary no-border" type="button"><i class="fas fa-arrow-left"></i></button>
      <h5>Write</h5>
    </div>

    <!-- Scroll Box -->
    <div class="scroll-content">

      <!-- Header Settings -->
      <div class="card card-padding text-left section-one">

        <h6>Header Settings</h6>
        
        <div class="row ">
          <div class="col-md-10 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Main Keyword <span class="text-danger">*</span></label> <span class="float-right">61/80</span>
              <input type="text" class="form-control" placeholder="What do dermatologist priscribe for skin whitening?">
            </div>
          </div>
          <div class="col-md-2 col-sm-5 col-xs-5">
            <div class="form-group mb-3">
              <button class="btn btn-primary mt-4" style="width:100%;">Generate Title</button>
            </div>
          </div>
        </div>

        <div class="row ">
          <div class="col-md-10 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Title <span class="text-danger">*</span></label> <span class="float-right">66/100</span>
              <input type="text" class="form-control" placeholder="What do dermatologist priscribe for skin whitening? Discover now!">
            </div>
          </div>
          <div class="col-md-2 col-sm-5 col-xs-5"></div>
        </div>
        
      </div>
        <!-- .section-one -->

      <!-- Core Settings -->
      <div class="text-left section-two ">
        <h6>Core Settings</h6>

        <div class="row ">
          <div class="col-md-5 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Language</label>
              <select name="" id="" class="form-control">
                <option value="">English (US)</option>
              </select>
            </div>

            <div class="form-group mb-3">
              <label for="">Tone of Voice</label>
              <select name="" id="" class="form-control">
                <option value="">Friendly</option>
              </select>
            </div>

            <div class="form-group mb-3">
              <label for="">Point of View</label>
              <select name="" id="" class="form-control">
                <option value="">None</option>
              </select>
            </div>

            <div class="form-group mb-3">
              <label for="">Target Country</label>
              <select name="" id="" class="form-control">
                <option value="">None</option>
              </select>
            </div>

          </div>
          <div class="col-md-6 col-sm-6 col-xs-6 row">
            <div class="col-md-6 mb-2">
              <div class="form-group ">
                <label for="">Article Size</label>
                <select name="" id="" class="form-control">
                  <option value="">X-Small</option>
                </select>
              </div>
            </div>
            <div class="col-md-6 mb-2">
              <div class="form-group ">
                <input type="text" class="form-control mt-4" disabled value="2400-3600 words, 9-12 headings">
              </div>
            </div>

            <div class="col-md-12 setting-details">
              <p>
                The x-small article offers short article or news, ideal for quick updates and capturing immediate interest, ensuring your content remains fresh and timely in the eyes of your audiences.
              </p>
              <div class="mb-2">
                Details to include <i class="fas fa-info-circle"></i> <span class="text-primary sample-box">Sample 1 | Sample 2 | Sample 3</span>
              </div>
              <label for="intendMode" class="mb-2">
                <input type="checkbox" id="intendMode">
                Intence mode: to each section, beyond just the entire article.
              </label>
              <textarea name="" class="form-control" id="" cols="30" rows="3" placeholder="e.g phone number as 267-229-6783"></textarea>
            </div>
            
          </div>
        </div>
        
      </div>
        <!-- .section-two -->

      <!-- Media Hub -->
      <div class="card card-padding text-left section-three">

        <h6>Media Hub</h6>
        
        <div class="row ">
          <div class="col-md-3 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">All Images</label>
                <select name="" id="" class="form-control">
                  <option value="">None</option>
                </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Number of Images</label>
                <select name="" id="" class="form-control">
                  <option value="">3</option>
                </select>
            </div>
          </div>

          <div class="col-md-3 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Image Style</label>
                <select name="" id="" class="form-control">
                  <option value="">None</option>
                </select>
            </div>
          </div>

          <div class="col-md-3 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Image Size</label>
                <select name="" id="" class="form-control">
                  <option value="">1344x768 (16:9)</option>
                </select>
            </div>
          </div>
          
          <div class="col-md-12">
            <label for="media1" class="mb-2">
                <input type="checkbox" id="media1">
                Include the main keyword in the first images as Alt-text. Relevant keyword will be picked up and added to the rest the images.
              </label>
          </div>

          <div class="row ">
            <div class="col-md-3 col-sm-7 col-xs-5">
              <div class="form-group mb-3">
                <label for="">Youtube Videos</label>
                  <select name="" id="" class="form-control">
                    <option value="">Yes</option>
                  </select>
              </div>
            </div>

            <div class="col-md-2 col-sm-7 col-xs-5">
              <div class="form-group mb-3">
                <label for="">Number of Videos</label>
                  <select name="" id="" class="form-control">
                    <option value="">1</option>
                  </select>
              </div>
            </div>

            <div class="col-md-3 col-sm-7 col-xs-5">
              <div class="form-group mb-3">
                <label for="">Layout Options</label>
                  <select name="" id="" class="form-control">
                    <option value="">Distribute evenly</option>
                  </select>
              </div>
            </div>
          </div>

          <div class="col-md-12">
            <label for="media2" class="mb-2">
                <input type="checkbox" id="media2">
                All media elements will be placed strictly under the headings. If disabled, the AI will decide and find the best placement.
              </label>
          </div>
          
        </div>
      </div>
        <!-- .section-three -->

      <!-- SEO -->
      <div class="card card-padding text-left section-four">

        <h6>SEO</h6>
        
        <div class="row ">
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">SEO Score</label>
                <select name="" id="" class="form-control">
                  <option value="">0-20%</option>
                </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Keyword Density</label>
                <select name="" id="" class="form-control">
                  <option value="">10 times</option>
                </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Tag</label>
                <select name="" id="" class="form-control">
                  <option value="">None</option>
                </select>
            </div>
          </div>

          <div class="col-md-12">
            <label for="seo1" class="mb-2">
                <input type="checkbox" id="seo1">
                Use the main keyword to write and insert a meta description in post. Also relevant keywords will be picked up and added to the meta description.
              </label>
          </div>
          
        </div>
      </div>
        <!-- .section-four -->

      <!-- Keywords to include in the text -->
      <div class="text-left section-five ">

        <div class="row mb-4">

          <h6>Keywords to include in the text</h6>

          <div class="col-md-9 col-sm-7 col-xs-5">
            <div class="form-group label-text ">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet, ab culpa voluptates ex
            </div>
          </div>

          <div class="col-md-3 col-sm-5 col-xs-5">
            <div class="form-group ">
              <button class="btn btn-primary" style="width:100%;">NLP Keyword Generator</button>
            </div>
          </div>

        </div>

        <div class="card card-padding text-left section-four">
          <div class="col-md-12 mb-3">

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">what do dermatologist prescribe for skin whitening? <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">dermatologist prescribe <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">dermatologist skin whitening treatment <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">skin dermatologist prescribe <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">skin whitening treatment <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">dermatologist skin whitening treatment <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">what do dermatologist prescribe for skin whitening? <i class="fas fa-times"></i></button>

            <button type="button" class="btn btn-secondary btn-sm keywords-tag">dermatologist prescribe <i class="fas fa-times"></i></button>

          </div>
          <label for="seo1" class="mb-2">
            Write some keyword or phrase  relevant to your blog, then press Enter or + to add
          </label>
        </div>

      </div>
        <!-- .section-five -->

      <!-- Structure -->
      <div class="text-left section-six ">
        <h6>Structure</h6>

        <div class="row ">
          
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Conclusion</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>
          
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Tables</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">H3</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">List</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>
          
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Italics</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Quotes</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Key Takeaway</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>
          
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">FAQs</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Bold</label>
              <select name="" id="" class="form-control">
                <option value="">Yes</option>
              </select>
            </div>
          </div>

        </div>
        
      </div>
        <!-- .section-six -->

      <!-- Connect to Web -->
      <div class="text-left section-seven ">
        <h6>Connect to Web</h6>

        <div class="row ">
          <div class="col-md-5 col-sm-7 col-xs-5 row">
            
            <div class="col-md-6 mb-2">
              <div class="form-group ">
                <label for="">Network</label>
                <select name="" id="" class="form-control">
                  <option value="">No</option>
                </select>
              </div>
            </div>
            <div class="col-md-6 mb-2">
              <div class="form-group ">
                <label for="">Source link</label>
                <select name="" id="" class="form-control">
                  <option value="">No</option>
                </select>
              </div>
            </div>

            <div class="form-group mb-3">
              <label for="">Search Source</label>
              <select name="" id="" class="form-control">
                <option value="">Real-Time Search Result</option>
              </select>
            </div>

          </div>
          <div class="col-md-6 col-sm-6 col-xs-6 row">
            
            <div class="col-md-12 setting-details">
              <label for="">Search Depth</label>
              <p>
                Quick finds from thematic sources and uses them as a factual basis for writing an article.
              </p>
              <p>
                The technology of Real-Time Search Results enables the immediate acquisition of search findings, which are then utilized for article writing.
              </p>
            </div>
            
          </div>
        </div>

        <div class="col-md-10">
          <label for="">URLs</label>
          <textarea name="" id="" cols="30" rows="3" class="form-control"></textarea>
        </div>
        
      </div>
        <!-- .section-seven -->

      <!-- Internal Link -->
      <div class="card card-padding text-left section-eight">

        <h6>Internal Link</h6>
        
        <div class="row ">
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Insert Internal Link</label>
                <select name="" id="" class="form-control">
                  <option value="">Yes</option>
                </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Number of Internal Link</label>
                <select name="" id="" class="form-control">
                  <option value="">5</option>
                </select>
            </div>
          </div>

          <div class="col-md-8 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Post Link</label>
              <textarea name="" id="" cols="30" rows="2" class="form-control" placeholder="Enter link url per line"></textarea>
            </div>
          </div>
          
        </div>
      </div>
        <!-- .section-eight -->

      <!-- Document -->
      <div class="text-left section-ten">

        <h6>Document</h6>
        
        <div class="row ">
          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Save a Directory</label>
              <select name="" id="" class="form-control">
                <option value="">Home</option>
              </select>
            </div>
          </div>

          <div class="col-md-2 col-sm-7 col-xs-5">
            <div class="form-group mt-4">
              <button class="btn btn-primary">Change</button>  
            </div>
          </div>
        </div>

        <!-- Publish to WordPress -->
        <div class="card card-padding text-left section-eight">

          <h6>Publish to WordPress</h6>
          
          <div class="row ">
            <div class="col-md-3 col-sm-7 col-xs-5">
              <div class="form-group mb-3">
                <label for="">Publication</label>
                  <select name="" id="" class="form-control">
                    <option value="">No</option>
                  </select>
              </div>
            </div>

            <div class="col-md-8 col-sm-7 col-xs-5">
              <div class="form-group mb-3">
                <label for="">Important</label>
                <p>
                  If you enable this option, all generated documents will be published on the selected site. Be careful with the settings and publication date.
                </p>
              </div>
            </div>
            
          </div>
        </div>
          <!-- .section-eight -->
        
      </div>
        <!-- .section-ten -->

      <!-- Language Model -->
      <div class="text-left section-eleven">

        <h6>Language Model</h6>
        
        <div class="row ">
          <div class="col-md-4 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">Quality Type</label>
              <select name="" id="" class="form-control">
                <option value="">GPT 3.5 + GPT 3.5 Turbo 16k + GPT 4</option>
              </select>
            </div>
          </div>

          <div class="col-md-8 col-sm-7 col-xs-5">
            <div class="form-group mt-4">
              <p class="label-text">For optimal results, we use a mix of different models including GPT 3.5, GPT 3.5 Turbo 16k, and GPT 4 8k,<br> ensuring the best quality.</p>
            </div>
          </div>
        </div>

        <div class="row ">
          <div class="col-md-4 col-sm-7 col-xs-5">
            <div class="form-group mb-3">
              <label for="">openAI API Key</label>
              <select name="" id="" class="form-control">
                <option value="">No</option>
              </select>
            </div>
          </div>

          <div class="col-md-8 col-sm-7 col-xs-5">
            <div class="form-group mt-4">
              <p class="label-text">You can connect your API Key if you have used up our words and still have unspent Article <br>Generation limits.</p>
            </div>
          </div>
        </div>

      </div>
        <!-- .section-eleven -->

      <!-- Write Button -->
      <div>
        <div class="col-md-12 write-btn">
          <button class="btn btn-primary"><i class="fas fa-pen"></i> Write</button>
        </div>
      </div>
      
    </div>
      <!-- .scroll-content -->
    
  </div>
</template>

<script>
export default {
  name: "Main",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.card-gap {
  margin-bottom: 30px;
}

.label-text {
  font-size: 13px;
  color: grey;
}

.float-right {
  float:right;
}

.keywords-tag {
  margin-left: 10px;
  margin-bottom: 15px;
}

.write-btn {
  text-align: right;

  button {
    width: 160px;

    i {
      margin-right: 6px;
    }
  }
}

#content {
  width: 100%;
  transition: all 0.3s;
  margin-top: 14px;
  border-radius: 5px;

  .section-one {
    .card-gap();
    
    label{
      .label-text();
    }

    input {
      &::placeholder{
        .label-text();
          color:#a3a3a3;
        }
    }
  }

  .section-two {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

    .setting-details {
      .label-text();
    }

    .sample-box {
      margin-left: 50px;
    }

  }


  .section-three {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
        color:#000;
      }
    }

  }

  .section-four {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
        color:#000;
      }
    }

  }

  .section-five {
    .card-gap();

    label{
      .label-text();
    }

  }

  .section-six {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

  }

  .section-seven {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

  }

  .section-eight {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

  }

  .section-ten {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

  }

  .section-eleven {
    .card-gap();

    label{
      .label-text();
    }

    select, input {
      &::placeholder{
        .label-text();
          color:#000;
        }
    }

  }
  
  .scroll-content {
    max-height: 600px;
    overflow: scroll;
    padding-right: 14px;
  }
}

.card-padding {
  padding: 25px;
}

.text-left{
  text-align: left;
}

.container-fluid {
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  margin-top: 10px;
}

.w-arrow {

  button {
    margin-right: 10px;
  }

  h5 {
    margin-top:6px;
    font-weight: bold;
  }

}



</style>
