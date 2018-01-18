<Type Name="DataMaskingRule" FullName="Microsoft.Azure.Management.Sql.Models.DataMaskingRule">
  <TypeSignature Language="C#" Value="public class DataMaskingRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataMaskingRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
  <TypeSignature Language="VB.NET" Value="Public Class DataMaskingRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DataMaskingRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="22be6-101">Stellt eine datenmaskierungsregel Datenbank dar.</span><span class="sxs-lookup"><span data-stu-id="22be6-101">Represents a database data masking rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22be6-102">Initialisiert eine neue Instanz der DataMaskingRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22be6-102">Initializes a new instance of the DataMaskingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule (string schemaName, string tableName, string columnName, Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id = null, string name = null, string type = null, string dataMaskingRuleId = null, string aliasName = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState = null, string numberFrom = null, string numberTo = null, string prefixSize = null, string suffixSize = null, string replacementString = null, string location = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schemaName, string tableName, string columnName, valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id, string name, string type, string dataMaskingRuleId, string aliasName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState, string numberFrom, string numberTo, string prefixSize, string suffixSize, string replacementString, string location, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingFunction,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState},System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schemaName As String, tableName As String, columnName As String, maskingFunction As DataMaskingFunction, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional dataMaskingRuleId As String = null, Optional aliasName As String = null, Optional ruleState As Nullable(Of DataMaskingRuleState) = null, Optional numberFrom As String = null, Optional numberTo As String = null, Optional prefixSize As String = null, Optional suffixSize As String = null, Optional replacementString As String = null, Optional location As String = null, Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule : string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingFunction * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingRule" Usage="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule (schemaName, tableName, columnName, maskingFunction, id, name, type, dataMaskingRuleId, aliasName, ruleState, numberFrom, numberTo, prefixSize, suffixSize, replacementString, location, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="columnName" Type="System.String" />
        <Parameter Name="maskingFunction" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingFunction" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="dataMaskingRuleId" Type="System.String" />
        <Parameter Name="aliasName" Type="System.String" />
        <Parameter Name="ruleState" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;" />
        <Parameter Name="numberFrom" Type="System.String" />
        <Parameter Name="numberTo" Type="System.String" />
        <Parameter Name="prefixSize" Type="System.String" />
        <Parameter Name="suffixSize" Type="System.String" />
        <Parameter Name="replacementString" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schemaName"><span data-ttu-id="22be6-103">Der Schemaname, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-103">The schema name on which the data masking rule is applied.</span></span></param>
        <param name="tableName"><span data-ttu-id="22be6-104">Der Tabellenname, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-104">The table name on which the data masking rule is applied.</span></span></param>
        <param name="columnName"><span data-ttu-id="22be6-105">Der Spaltenname, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-105">The column name on which the data masking rule is applied.</span></span></param>
        <param name="maskingFunction"><span data-ttu-id="22be6-106">Das Maskierungsfunktion, die für die datenmaskierungsregel verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-106">The masking function that is used for the data masking rule.</span></span> <span data-ttu-id="22be6-107">Folgende Werte sind möglich: 'Default', "CCN", "Email", "Zahl", "SSN", "Text"</span><span class="sxs-lookup"><span data-stu-id="22be6-107">Possible values include: 'Default', 'CCN', 'Email', 'Number', 'SSN', 'Text'</span></span></param>
        <param name="id"><span data-ttu-id="22be6-108">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="22be6-108">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="22be6-109">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="22be6-109">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="22be6-110">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="22be6-110">Resource type.</span></span></param>
        <param name="dataMaskingRuleId"><span data-ttu-id="22be6-111">Die Regel-ID</span><span class="sxs-lookup"><span data-stu-id="22be6-111">The rule Id.</span></span></param>
        <param name="aliasName"><span data-ttu-id="22be6-112">Der Aliasname.</span><span class="sxs-lookup"><span data-stu-id="22be6-112">The alias name.</span></span> <span data-ttu-id="22be6-113">Dies ist ein legacy-Parameter und wird nicht mehr verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-113">This is a legacy parameter and is no longer used.</span></span></param>
        <param name="ruleState"><span data-ttu-id="22be6-114">Der Regelstatus.</span><span class="sxs-lookup"><span data-stu-id="22be6-114">The rule state.</span></span> <span data-ttu-id="22be6-115">Löschen eine Regel verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-115">Used to delete a rule.</span></span> <span data-ttu-id="22be6-116">Um eine vorhandene Regel zu löschen, geben Sie die SchemaName, der Tabellenname, der Spaltenname, MaskingFunction, und RuleState als deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="22be6-116">To delete an existing rule, specify the schemaName, tableName, columnName, maskingFunction, and specify ruleState as disabled.</span></span>
            <span data-ttu-id="22be6-117">Wenn die Regel bereits vorhanden ist, wird die Regel mit RuleState festgelegt aktiviert ist, unabhängig vom angegebenen Wert des RuleState erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="22be6-117">However, if the rule doesn't already exist, the rule will be created with ruleState set to enabled, regardless of the provided value of ruleState.</span></span> <span data-ttu-id="22be6-118">Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</span><span class="sxs-lookup"><span data-stu-id="22be6-118">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="numberFrom"><span data-ttu-id="22be6-119">Die von der maskierungsregel NumberFrom-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="22be6-119">The numberFrom property of the masking rule.</span></span> <span data-ttu-id="22be6-120">Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-120">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span></param>
        <param name="numberTo"><span data-ttu-id="22be6-121">Die von der die datenmaskierungsregel NumberTo-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="22be6-121">The numberTo property of the data masking rule.</span></span> <span data-ttu-id="22be6-122">Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-122">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span></param>
        <param name="prefixSize"><span data-ttu-id="22be6-123">Wenn MaskingFunction auf Text, die Anzahl der Zeichen am Anfang der Zeichenfolge ohne Maskierung angezeigt festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-123">If maskingFunction is set to Text, the number of characters to show unmasked in the beginning of the string.</span></span> <span data-ttu-id="22be6-124">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-124">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="suffixSize"><span data-ttu-id="22be6-125">Wenn MaskingFunction auf Text, die Anzahl der Zeichen am Ende der Zeichenfolge ohne Maskierung angezeigt festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-125">If maskingFunction is set to Text, the number of characters to show unmasked at the end of the string.</span></span>
            <span data-ttu-id="22be6-126">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-126">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="replacementString"><span data-ttu-id="22be6-127">Wenn MaskingFunction auf Text, das Zeichen, das zum Maskieren der nicht offen gelegten Teils der Zeichenfolge festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-127">If maskingFunction is set to Text, the character to use for masking the unexposed part of the string.</span></span>
            <span data-ttu-id="22be6-128">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-128">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="location"><span data-ttu-id="22be6-129">Der Speicherort der datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="22be6-129">The location of the data masking rule.</span></span></param>
        <param name="kind"><span data-ttu-id="22be6-130">Die Art der Datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="22be6-130">The kind of Data Masking Rule.</span></span> <span data-ttu-id="22be6-131">Metadaten für die Azure-Portal verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-131">Metadata, used for Azure portal.</span></span></param>
        <summary>
            <span data-ttu-id="22be6-132">Initialisiert eine neue Instanz der DataMaskingRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22be6-132">Initializes a new instance of the DataMaskingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasName">
      <MemberSignature Language="C#" Value="public string AliasName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberSignature Language="VB.NET" Value="Public Property AliasName As String" />
      <MemberSignature Language="F#" Value="member this.AliasName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.aliasName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-133">Ruft ab oder legt den Aliasnamen fest.</span><span class="sxs-lookup"><span data-stu-id="22be6-133">Gets or sets the alias name.</span></span> <span data-ttu-id="22be6-134">Dies ist ein legacy-Parameter und wird nicht mehr verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-134">This is a legacy parameter and is no longer used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnName">
      <MemberSignature Language="C#" Value="public string ColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnName As String" />
      <MemberSignature Language="F#" Value="member this.ColumnName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columnName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-135">Ruft ab oder legt den Namen der Spalte, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-135">Gets or sets the column name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingRuleId">
      <MemberSignature Language="C#" Value="public string DataMaskingRuleId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataMaskingRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingRuleId As String" />
      <MemberSignature Language="F#" Value="member this.DataMaskingRuleId : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-136">Ruft die Regel-ID ab</span><span class="sxs-lookup"><span data-stu-id="22be6-136">Gets the rule Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-137">Ruft die Art der Datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="22be6-137">Gets the kind of Data Masking Rule.</span></span> <span data-ttu-id="22be6-138">Metadaten für die Azure-Portal verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-138">Metadata, used for Azure portal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-139">Ruft den Speicherort der datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="22be6-139">Gets the location of the data masking rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaskingFunction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberSignature Language="VB.NET" Value="Public Property MaskingFunction As DataMaskingFunction" />
      <MemberSignature Language="F#" Value="member this.MaskingFunction : Microsoft.Azure.Management.Sql.Models.DataMaskingFunction with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maskingFunction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingFunction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-140">Ruft ab oder legt die Maskierungsfunktion, die für die datenmaskierungsregel verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-140">Gets or sets the masking function that is used for the data masking rule.</span></span> <span data-ttu-id="22be6-141">Folgende Werte sind möglich: 'Default', "CCN", "Email", "Zahl", "SSN", "Text"</span><span class="sxs-lookup"><span data-stu-id="22be6-141">Possible values include: 'Default', 'CCN', 'Email', 'Number', 'SSN', 'Text'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberFrom">
      <MemberSignature Language="C#" Value="public string NumberFrom { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberFrom As String" />
      <MemberSignature Language="F#" Value="member this.NumberFrom : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberFrom")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-142">Ruft ab, oder legt ihn fest NumberFrom-Eigenschaft der Maskierung.</span><span class="sxs-lookup"><span data-stu-id="22be6-142">Gets or sets the numberFrom property of the masking rule.</span></span> <span data-ttu-id="22be6-143">Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-143">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberTo">
      <MemberSignature Language="C#" Value="public string NumberTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberTo As String" />
      <MemberSignature Language="F#" Value="member this.NumberTo : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-144">Ruft ab oder legt die NumberTo-Eigenschaft der datenmaskierungsregel.</span><span class="sxs-lookup"><span data-stu-id="22be6-144">Gets or sets the numberTo property of the data masking rule.</span></span>
            <span data-ttu-id="22be6-145">Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-145">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefixSize">
      <MemberSignature Language="C#" Value="public string PrefixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrefixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefixSize As String" />
      <MemberSignature Language="F#" Value="member this.PrefixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.prefixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-146">Ruft ab oder legt fest, ob der Text, die Anzahl der Zeichen am Anfang der Zeichenfolge ohne Maskierung angezeigt MaskingFunction angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-146">Gets or sets if maskingFunction is set to Text, the number of characters to show unmasked in the beginning of the string.</span></span>
            <span data-ttu-id="22be6-147">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-147">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacementString">
      <MemberSignature Language="C#" Value="public string ReplacementString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplacementString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplacementString As String" />
      <MemberSignature Language="F#" Value="member this.ReplacementString : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replacementString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-148">Ruft ab oder legt fest, ob MaskingFunction auf Text, das Zeichen, das zum Maskieren der nicht offen gelegten Teils der Zeichenfolge festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-148">Gets or sets if maskingFunction is set to Text, the character to use for masking the unexposed part of the string.</span></span> <span data-ttu-id="22be6-149">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-149">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleState As Nullable(Of DataMaskingRuleState)" />
      <MemberSignature Language="F#" Value="member this.RuleState : Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-150">Ruft ab oder legt den Regelstatus fest.</span><span class="sxs-lookup"><span data-stu-id="22be6-150">Gets or sets the rule state.</span></span> <span data-ttu-id="22be6-151">Löschen eine Regel verwendet.</span><span class="sxs-lookup"><span data-stu-id="22be6-151">Used to delete a rule.</span></span> <span data-ttu-id="22be6-152">Um eine vorhandene Regel zu löschen, geben Sie die SchemaName, der Tabellenname, der Spaltenname, MaskingFunction, und RuleState als deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="22be6-152">To delete an existing rule, specify the schemaName, tableName, columnName, maskingFunction, and specify ruleState as disabled.</span></span> <span data-ttu-id="22be6-153">Wenn die Regel bereits vorhanden ist, wird die Regel mit RuleState festgelegt aktiviert ist, unabhängig vom angegebenen Wert des RuleState erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="22be6-153">However, if the rule doesn't already exist, the rule will be created with ruleState set to enabled, regardless of the provided value of ruleState.</span></span>
            <span data-ttu-id="22be6-154">Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</span><span class="sxs-lookup"><span data-stu-id="22be6-154">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-155">Ruft ab oder legt den Schemanamen, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-155">Gets or sets the schema name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuffixSize">
      <MemberSignature Language="C#" Value="public string SuffixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SuffixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property SuffixSize As String" />
      <MemberSignature Language="F#" Value="member this.SuffixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-156">Ruft ab oder legt fest, ob der Text, die Anzahl der Zeichen am Ende der Zeichenfolge ohne Maskierung angezeigt MaskingFunction angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="22be6-156">Gets or sets if maskingFunction is set to Text, the number of characters to show unmasked at the end of the string.</span></span> <span data-ttu-id="22be6-157">Andernfalls wird dieser Parameter ignoriert.</span><span class="sxs-lookup"><span data-stu-id="22be6-157">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22be6-158">Ruft ab oder legt den Namen der Tabelle, auf dem die Data Masking-Regel angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="22be6-158">Gets or sets the table name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataMaskingRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22be6-159">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="22be6-159">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="22be6-160">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="22be6-160">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>