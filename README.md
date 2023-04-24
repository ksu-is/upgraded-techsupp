# upgraded-techsupp

The objective of this project is to be used for technical concerns and lay a foundation for other software. It will include anything from checking for malicious files, to analyzing the domain, and will also help to cut down on research time. This will allow room to help researchers and coders to find their way easier and faster when researching a broad topic and looking for specific answers.

git clone https://github.com/Qafoo/QualityAnalyzer.git
cd QualityAnalyzer
composer install
bin/analyze analyze src/php/
bin/analyze list:analyzers
bin/analyze \
    --coverage=/path/to/clover.xml \
    --tests=/path/to/junit.xml \
    --exclude=libraries,vendor \
    analyze /path/to/source
bin/analyze \
    --exclude_analyzers=git,gitDetailed \
    analyze /path/to/source
    bin/analyze serve