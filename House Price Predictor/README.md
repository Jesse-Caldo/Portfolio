# House price analysis
This project uses this dataset [https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset]

# Dataset Cleaning
- dropped unneeded columns (ID)

# Models
- Linear regression model
- Random Forest

# Features Needed
- MSSubClass - int
- MSZoning - ['RL', 'RM', 'C (all)', 'FV', 'RH']
- LotFrontage - float
- LotArea - int 
- Street - ['Pave', 'Grvl']
- Alley - ['Pave', 'Grvl']
- LotShape - ['Reg', 'IR1', 'IR2', 'IR3']
- LandContour - ['Lvl', 'Bnk', 'Low', 'HLS']
- Utilities - ['AllPub', 'NoSeWa']
- LotConfig - ['Inside', 'FR2', 'Corner', 'CulDSac', 'FR3']
- LandSlope - ['Gtl', 'Mod', 'Sev']
- Neighborhood - ['CollgCr', 'Veenker', 'Crawfor', 'NoRidge', 'Mitchel', 'Somerst', 'NWAmes', 'OldTown', 'BrkSide', 'Sawyer', 'NridgHt', 'NAmes', 'SawyerW', 'IDOTRR', 'MeadowV', 'Edwards', 'Timber', 'Gilbert', 'StoneBr', 'ClearCr', 'NPkVill', 'Blmngtn', 'BrDale', 'SWISU', 'Blueste']
- Condition1 - ['Norm', 'Artery', 'RRNn', 'Feedr', 'PosN', 'PosA', 'RRAn', 'RRAe']
- Condition2 - ['Norm', 'Artery', 'RRNn', 'Feedr', 'PosN', 'PosA', 'RRAn', 'RRAe']
- BldgType - ['1Fam', '2fmCon', 'Duplex', 'TwnhsE', 'Twnhs']a
- HouseStyle - ['2Story', '1Story', '1.5Fin', '1.5Unf', 'SFoyer', 'SLvl', '2.5Unf',
       '2.5Fin']
- OverallQual - [1 - 10]
- OverallCond - [1 - 10]
- YearBuilt - 
- YearRemodAdd - 
- RoofStyle - ['Gable', 'Hip', 'Gambrel', 'Mansard', 'Flat', 'Shed']
- RoofMatl - ['CompShg', 'WdShngl', 'Metal', 'WdShake', 'Membran', 'Tar&Grv',
       'Roll', 'ClyTile']
- Exterior1st - ['VinylSd', 'MetalSd', 'Wd Sdng', 'HdBoard', 'BrkFace', 'WdShing',
       'CemntBd', 'Plywood', 'AsbShng', 'Stucco', 'BrkComm', 'AsphShn',
       'Stone', 'ImStucc', 'CBlock']
- Exterior2nd - ['VinylSd', 'MetalSd', 'Wd Sdng', 'HdBoard', 'BrkFace', 'WdShing',
       'CemntBd', 'Plywood', 'AsbShng', 'Stucco', 'BrkComm', 'AsphShn',
       'Stone', 'ImStucc', 'CBlock']
- MasVnrType - ['BrkFace', 'None', 'Stone', 'BrkCmn', nan]
- MasVnrArea - 
- ExterQual - ['Gd', 'TA', 'Ex', 'Fa']
- ExterCond - ['Gd', 'TA', 'Ex', 'Fa']
- Foundation - ['PConc', 'CBlock', 'BrkTil', 'Wood', 'Slab', 'Stone']
- BsmtQual - ['Gd', 'TA', 'Ex', 'Fa']
- BsmtCond - ['Gd', 'TA', 'Ex', 'Fa']
- BsmtExposure - ['No', 'Gd', 'Mn', 'Av', nan]
- BsmtFinType1 - ['GLQ', 'ALQ', 'Unf', 'Rec', 'BLQ', nan, 'LwQ']
- BsmtFinSF1 - int
- BsmtFinType2 - ['GLQ', 'ALQ', 'Unf', 'Rec', 'BLQ', nan, 'LwQ']
- BsmtFinSF2 - int
- BsmtUnfSF - int
- TotalBsmtSF - int
- Heating - ['GasA', 'GasW', 'Grav', 'Wall', 'OthW', 'Floor']
- HeatingQC - ['Ex', 'Gd', 'TA', 'Fa', 'Po']
- CentralAir - ['Y', 'N']
- Electrical - ['SBrkr', 'FuseF', 'FuseA', 'FuseP', 'Mix', nan]
- 1stFlrSF - int
- 2ndFlrSF - int
- LowQualFinSF - int
- GrLivArea - int
- BsmtFullBath - int
- BsmtHalfBath - int
- FullBath - int
- HalfBath - int
- BedroomAbvGr - int
- KitchenAbvGr - int
- KitchenQual - ['Ex', 'Gd', 'TA', 'Fa', 'Po']
- TotRmsAbvGrd - int
- Functional - ['Typ', 'Min1', 'Maj1', 'Min2', 'Mod', 'Maj2', 'Sev']
- Fireplaces - int
- FireplaceQu - [nan, 'TA', 'Gd', 'Fa', 'Ex', 'Po']
- GarageType - ['Attchd', 'Detchd', 'BuiltIn', 'CarPort', nan, 'Basment', '2Types']
- GarageYrBlt -int 
- GarageFinish - ['RFn', 'Unf', 'Fin', nan]
- GarageCars - int
- GarageArea - int
- GarageQual - ['TA', 'Fa', 'Gd', nan, 'Ex', 'Po']
- GarageCond - ['TA', 'Fa', nan, 'Gd', 'Po', 'Ex']
- PavedDrive - ['Y', 'N', 'P']
- WoodDeckSF - int
- OpenPorchSF - int
- EnclosedPorch - int
- 3SsnPorch - int
- ScreenPorch - int
- PoolArea - int
- PoolQC - [nan, 'Ex', 'Fa', 'Gd']
- Fence - [nan, 'MnPrv', 'GdWo', 'GdPrv', 'MnWw']
- MiscFeature - [nan, 'Shed', 'Gar2', 'Othr', 'TenC']
- MiscVal - int
- MoSold - int
- YrSold - int
- SaleType -['WD', 'New', 'COD', 'ConLD', 'ConLI', 'CWD', 'ConLw', 'Con', 'Oth'] 
- SaleCondition - ['Normal', 'Abnorml', 'Partial', 'AdjLand', 'Alloca', 'Family']
- SalePrice - int