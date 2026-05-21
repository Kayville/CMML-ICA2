根据获得SCE训练scDesign3，生成三种dataset，每种输出两个模拟集
通用：assay_use = "counts"，family_use = "nb"，celltype = "author_cell_type"，other_covariates = c("condition", "batch")，pseudotime = NULL，spatial = NULL，corr_formula = "author_cell_type"，copula = "gaussian"，if_sparse = TRUE，ncell = 5000，sigma_formula = "1"
Dataset1：mu_formula = "author_cell_type + condition"，比例为balanced
2："author_cell_type + condition + batch"，比例balanced，
3：mu_formula = "author_cell_type + condition"，比例dExN：RG：InhN大约是13:7:2。” 
