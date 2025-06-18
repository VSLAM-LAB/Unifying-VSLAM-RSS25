---
id: accepted-papers
name: Accepted Papers
heading: Accepted Papers
div_class: lead
# subheading: Will Catch Your Eye
# image: "http://placehold.it/500x500"
---

<div style="padding: 10px; border: 1px solid #ddd; border-radius: 8px; margin-bottom: 10px;">
    <!-- <p><strong><span style="color: red;">Winner of the Outstanding Workshop Presentation Award</span></strong></p> -->
    <strong>On the Potential of Visual Place Recognition for Visual SLAM</strong> 
    <a href="assets/proceedings/Schubert_RSS2025_WorkshopUnifyingVSLAM.pdf" style="text-decoration: none; color: #007bff;">[Paper]</a> 
    <a href="assets/proceedings/Schubert_Poster_RSS2025_WorkshopUnifyingVSLAM.pdf" style="text-decoration: none; color: #007bff;">[Poster]</a><br>
    Stefan Schubert<br>
    
    <details>
        <summary style="font-size: 16px; color: #007bff; cursor: pointer; list-style: none; display: inline;">
            <span id="toggle-icon" style="display: inline-block; transform: rotate(0deg); transition: transform 0.3s;">▶</span>
            Poster Thumbnail
        </summary>
        <div style="margin-top: 10px;">
            <img src="assets/proceedings/tax/poster.png" alt="Poster Thumbnail" style="width: 800px; border: 1px solid #ddd; border-radius: 8px;">
        </div>
    </details>
</div>

<script>
    document.addEventListener('DOMContentLoaded', function () {
        document.querySelectorAll('details').forEach(function(detail) {
            detail.addEventListener('toggle', function() {
                var icon = this.querySelector('#toggle-icon');
                if (this.open) {
                    icon.style.transform = 'rotate(90deg)';
                } else {
                    icon.style.transform = 'rotate(0deg)';
                }
            });
        });
    });
</script>

