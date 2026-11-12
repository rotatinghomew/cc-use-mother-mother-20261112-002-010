测试：python3 -m unittest discover -s tests/threshold_experiments -p 'test_*.py'
构建：python3 -m compileall -q warning_threshold_lab tests/threshold_experiments
验收：python3 -m warning_threshold_lab.experiments.command fixtures/demo.json --database /tmp/warning_threshold_lab-acceptance.sqlite3
