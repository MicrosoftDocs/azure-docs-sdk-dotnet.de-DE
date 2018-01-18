<Type Name="USqlExternalDataSource" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource">
  <TypeSignature Language="C#" Value="public class USqlExternalDataSource : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlExternalDataSource extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlExternalDataSource&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlExternalDataSource = class&#xA;    inherit CatalogItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2af3f-101">Ein Data Lake Analytics U-SQL externe Datenquelle Katalogelement.</span><span class="sxs-lookup"><span data-stu-id="2af3f-101">A Data Lake Analytics catalog U-SQL external datasource item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlExternalDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-102">Initialisiert eine neue Instanz der USqlExternalDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2af3f-102">Initializes a new instance of the USqlExternalDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlExternalDataSource (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string name = null, string provider = null, string providerString = null, System.Collections.Generic.IList&lt;string&gt; pushdownTypes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string name, string provider, string providerString, class System.Collections.Generic.IList`1&lt;string&gt; pushdownTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional name As String = null, Optional provider As String = null, Optional providerString As String = null, Optional pushdownTypes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource : string * Nullable&lt;Guid&gt; * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource (computeAccountName, version, databaseName, name, provider, providerString, pushdownTypes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="providerString" Type="System.String" />
        <Parameter Name="pushdownTypes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="2af3f-103">der Name des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="2af3f-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="2af3f-104">die Version des Katalogelements.</span><span class="sxs-lookup"><span data-stu-id="2af3f-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="2af3f-105">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="2af3f-105">the name of the database.</span></span></param>
        <param name="name"><span data-ttu-id="2af3f-106">Der Name der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2af3f-106">the name of the external data source.</span></span></param>
        <param name="provider"><span data-ttu-id="2af3f-107">der Name des Anbieters für die externe Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2af3f-107">the name of the provider for the external data source.</span></span></param>
        <param name="providerString"><span data-ttu-id="2af3f-108">der Name der Anbieterzeichenfolge für die externe Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2af3f-108">the name of the provider string for the external data source.</span></span></param>
        <param name="pushdownTypes"><span data-ttu-id="2af3f-109">die Liste von Typen, die aus der externen Datenquelle nach unten verschoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="2af3f-109">the list of types to push down from the external data source.</span></span></param>
        <summary>
            <span data-ttu-id="2af3f-110">Initialisiert eine neue Instanz der USqlExternalDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2af3f-110">Initializes a new instance of the USqlExternalDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-111">Ruft ab oder legt den Namen der Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="2af3f-111">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="externalDataSourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-112">Ruft ab oder legt den Namen der externen Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2af3f-112">Gets or sets the name of the external data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-113">Ruft ab oder legt den Namen des Anbieters für die externe Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="2af3f-113">Gets or sets the name of the provider for the external data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProviderString">
      <MemberSignature Language="C#" Value="public string ProviderString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProviderString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.ProviderString" />
      <MemberSignature Language="VB.NET" Value="Public Property ProviderString As String" />
      <MemberSignature Language="F#" Value="member this.ProviderString : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.ProviderString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providerString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-114">Ruft ab oder legt den Namen der Zeichenfolge des Anbieters für die externe Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2af3f-114">Gets or sets the name of the provider string for the external data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushdownTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PushdownTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PushdownTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.PushdownTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property PushdownTypes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PushdownTypes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource.PushdownTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pushdownTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af3f-115">Ruft ab oder legt die Liste von Typen, die aus der externen Datenquelle nach unten verschoben.</span><span class="sxs-lookup"><span data-stu-id="2af3f-115">Gets or sets the list of types to push down from the external data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>