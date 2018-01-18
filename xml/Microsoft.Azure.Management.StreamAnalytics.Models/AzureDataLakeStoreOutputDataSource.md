<Type Name="AzureDataLakeStoreOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.DataLake/Accounts")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="975a6-101">Beschreibt eine Datenquelle für Azure Data Lake-Speicher-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="975a6-101">Describes an Azure Data Lake Store output data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="975a6-102">Initialisiert eine neue Instanz der AzureDataLakeStoreOutputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="975a6-102">Initializes a new instance of the AzureDataLakeStoreOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreOutputDataSource (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null, string accountName = null, string tenantId = null, string filePathPrefix = null, string dateFormat = null, string timeFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName, string accountName, string tenantId, string filePathPrefix, string dateFormat, string timeFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null, Optional accountName As String = null, Optional tenantId As String = null, Optional filePathPrefix As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource (refreshToken, tokenUserPrincipalName, tokenUserDisplayName, accountName, tenantId, filePathPrefix, dateFormat, timeFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="filePathPrefix" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken"><span data-ttu-id="975a6-103">Ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="975a6-103">A refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="975a6-104">Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-104">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="975a6-105">Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="975a6-105">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="975a6-106">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="tokenUserPrincipalName"><span data-ttu-id="975a6-107">Prinzipalname (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-107">The user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-108">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-108">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <param name="tokenUserDisplayName"><span data-ttu-id="975a6-109">Der Anzeigename des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-109">The user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-110">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-110">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <param name="accountName"><span data-ttu-id="975a6-111">Der Name des Kontos für Azure Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="975a6-111">The name of the Azure Data Lake Store account.</span></span> <span data-ttu-id="975a6-112">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="tenantId"><span data-ttu-id="975a6-113">Die Mandanten-Id des Benutzers verwendet, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-113">The tenant id of the user used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-114">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-114">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="filePathPrefix"><span data-ttu-id="975a6-115">Der Speicherort der Datei, in die Ausgabe geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="975a6-115">The location of the file to which the output should be written to.</span></span> <span data-ttu-id="975a6-116">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-116">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="dateFormat"><span data-ttu-id="975a6-117">Das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="975a6-117">The date format.</span></span> <span data-ttu-id="975a6-118">Wenn {Date} in der FilePathPrefix angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="975a6-118">Wherever {date} appears in filePathPrefix, the value of this property is used as the date format instead.</span></span></param>
        <param name="timeFormat"><span data-ttu-id="975a6-119">Das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="975a6-119">The time format.</span></span> <span data-ttu-id="975a6-120">Wenn {Time} in der FilePathPrefix angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="975a6-120">Wherever {time} appears in filePathPrefix, the value of this property is used as the time format instead.</span></span></param>
        <summary>
            <span data-ttu-id="975a6-121">Initialisiert eine neue Instanz der AzureDataLakeStoreOutputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="975a6-121">Initializes a new instance of the AzureDataLakeStoreOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-122">Ruft ab oder legt den Namen des Kontos für Azure Data Lake-Speicher.</span><span class="sxs-lookup"><span data-stu-id="975a6-122">Gets or sets the name of the Azure Data Lake Store account.</span></span>
            <span data-ttu-id="975a6-123">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-123">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-124">Ruft ab oder legt das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="975a6-124">Gets or sets the date format.</span></span> <span data-ttu-id="975a6-125">Wenn {Date} in der FilePathPrefix angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="975a6-125">Wherever {date} appears in filePathPrefix, the value of this property is used as the date format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePathPrefix">
      <MemberSignature Language="C#" Value="public string FilePathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.FilePathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.FilePathPrefix : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.FilePathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filePathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-126">Ruft ab oder legt den Speicherort der Datei, in die Ausgabe geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="975a6-126">Gets or sets the location of the file to which the output should be written to.</span></span> <span data-ttu-id="975a6-127">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-127">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-128">Ruft ab oder legt ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="975a6-128">Gets or sets a refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="975a6-129">Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-129">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="975a6-130">Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="975a6-130">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="975a6-131">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-131">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-132">Ruft ab oder legt die Mandanten-Id des Benutzers verwendet, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-132">Gets or sets the tenant id of the user used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-133">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="975a6-133">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-134">Ruft ab oder legt das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="975a6-134">Gets or sets the time format.</span></span> <span data-ttu-id="975a6-135">Wenn {Time} in der FilePathPrefix angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="975a6-135">Wherever {time} appears in filePathPrefix, the value of this property is used as the time format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-136">Ruft ab oder legt den Benutzernamen für die Anzeige des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-136">Gets or sets the user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-137">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-137">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="975a6-138">Ruft ab oder legt den Benutzerprinzipalnamen (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-138">Gets or sets the user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="975a6-139">Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="975a6-139">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>