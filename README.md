USE [489_BAMS]
GO

/****** Object:  Table [dbo].[Art]    Script Date: 2/25/2020 7:08:40 PM ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[Art](
	[Artid] [int] NOT NULL,
	[Artistid] [nchar](10) NOT NULL,
	[Locationid] [nchar](10) NOT NULL,
	[Title] [nchar](10) NULL,
	[Type] [nchar](10) NULL,
	[Description] [nchar](10) NULL,
	[Collection] [nchar](10) NULL,
	[Status] [nchar](10) NULL,
	[Purchase_Price] [nchar](10) NULL,
	[Value] [nchar](10) NULL,
	[Acquireddt] [date] NULL,
	[Available] [bit] NULL,
	[Media] [nchar](10) NULL,
	[Primary_Artist] [nchar](10) NULL,
	[Purchase_ID] [nchar](10) NULL,
 CONSTRAINT [PK_Art] PRIMARY KEY CLUSTERED 
(
	[Artid] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]
GO

