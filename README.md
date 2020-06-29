# World development indicators - Exploratory Data Analysis Using SQL
One liner: "Exploring country development indicators around the world"

# Tables
Tables and their fields are as follows: 
- Country(CountryCode, ShortName, TableName, LongName, Alpha2Code, CurrencyUnit, SpecialNotes, Region, IncomeGroup, Wb2Code, NationalAccountsBaseYear, NationalAccountsReferenceYear, SnaPriceValuation, LendingCategory, OtherGroups, SystemOfNationalAccounts, AlternativeConversionFactor, PppSurveyYear, BalanceOfPaymentManualInUse, ExternalDebtReportingStatus, SystemofTrade, GovernmentAccountingConcept, ImfDataDissemincationStandard, LatestPopulationCensus, LatestHouseholdSurvey, SourceofMostRecentIncomeandExpenditureData, VitalRegistrationComplete, LatestAgriculturalCensus, LatestIndustrialData, LatestTradeData, LatestWaterWithdrawalData)
- CountryNotes(CountryCode, SeriesCode, Description)
- FootNotes(CountryCode, Seriescode, Year, Description)
- Indicators(CountryName, CountryCode, IndicatorName, IndicatorCode, Year, Value)
- Series(SeriesCode, Topic, IndicatorName, ShortDefinition, LongDefinition, UnitOfMeasure, Periodicity, BasePeriod, OtherNotes, AggregationMethod, LimitationsAndExceptions, NotesFromOriginalSource, GeneralComments, Source, StatisticalConceptAndMethodoly, DevelopmentRelevance, RelatedSourceLinks, OtherWebLinks, RelatedLinks, LicenseType)
- SeriesNotes(SeriesCode, Year, Description)

# Table of Content
- Explore Indicators Table
- Filtering
- Aggregating And Summarizing
- JOINS
- Using Case WHEN
- Window Function
- Common Table Expression(CTE)
Please note: The dataset can be found here: https://www.kaggle.com/worldbank/world-development-indicators
