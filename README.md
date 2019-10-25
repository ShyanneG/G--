# Biocompute Object Composer by Seven Bridges

This project contains the Biocompute Object composer app shared with the CGC community.

To run the app:

- Click "Interactive Analysis", then open "Data Cruncher".
- Click "Create your first analysis", select "RStudio" and start the analysis.

When the editor is launched, switch to the "Terminal" tab in the lower left panel, run the following commands to copy the app from the project to the analysis session:

```bash
cp /sbgenomics/project-files/biocompute-composer.zip /sbgenomics/workspace/
unzip -q /sbgenomics/workspace/biocompute-composer.zip
rm /sbgenomics/workspace/biocompute-composer.zip
```

- Go to the `biocompute-composer` folder in the files panel (lower right), open and run through the code in `app-setup.R` to setup the environment (use Ctrl + Enter to run the code line-by-line).
- Open `app.R`, click the "Run App" button in the code editor panel to run the app.
- A dialog about popup windows may appear if you're running this for the first time, click "Try Again" to proceed.

Note: if running the app from a restarted analysis session, remember to run `app-setup.R` again before running the app.

## Legal

Copyright (C) 2019 Seven Bridges Genomics Inc. All rights reserved.

This document is the property of Seven Bridges Genomics Inc.
It is considered confidential and proprietary.

This document may not be reproduced or transmitted in any form,
in whole or in part, without the express written permission of
Seven Bridges Genomics Inc.
