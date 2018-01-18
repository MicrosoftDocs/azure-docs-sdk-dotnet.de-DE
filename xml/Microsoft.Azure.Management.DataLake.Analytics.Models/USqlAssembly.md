<Type Name="USqlAssembly" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly">
  <TypeSignature Language="C#" Value="public class USqlAssembly : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlAssembly extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlAssembly&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlAssembly = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="fcb3c-101">Ein Data Lake Analytics-Katalog U-SQL-Assembly.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-101">A Data Lake Analytics catalog U-SQL Assembly.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssembly ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-102">Initialisiert eine neue Instanz der USqlAssembly-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-102">Initializes a new instance of the USqlAssembly class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssembly (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string name = null, string clrName = null, Nullable&lt;bool&gt; isVisible = null, Nullable&lt;bool&gt; isUserDefined = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; files = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; dependencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string name, string clrName, valuetype System.Nullable`1&lt;bool&gt; isVisible, valuetype System.Nullable`1&lt;bool&gt; isUserDefined, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; files, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; dependencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional name As String = null, Optional clrName As String = null, Optional isVisible As Nullable(Of Boolean) = null, Optional isUserDefined As Nullable(Of Boolean) = null, Optional files As IList(Of USqlAssemblyFileInfo) = null, Optional dependencies As IList(Of USqlAssemblyDependencyInfo) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly : string * Nullable&lt;Guid&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly (computeAccountName, version, databaseName, name, clrName, isVisible, isUserDefined, files, dependencies)" />
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
        <Parameter Name="clrName" Type="System.String" />
        <Parameter Name="isVisible" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isUserDefined" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="files" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt;" />
        <Parameter Name="dependencies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="fcb3c-103">der Name des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="fcb3c-104">die Version des Katalogelements.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="fcb3c-105">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-105">the name of the database.</span></span></param>
        <param name="name"><span data-ttu-id="fcb3c-106">der Name der Assembly.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-106">the name of the assembly.</span></span></param>
        <param name="clrName"><span data-ttu-id="fcb3c-107">der Name der CLR.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-107">the name of the CLR.</span></span></param>
        <param name="isVisible"><span data-ttu-id="fcb3c-108">der Schalter, der angibt, ob diese Assembly sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-108">the switch indicating if this assembly is visible or not.</span></span></param>
        <param name="isUserDefined"><span data-ttu-id="fcb3c-109">der Schalter, der angibt, ob diese Assembly befindet sich eine benutzerdefinierte oder nicht.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-109">the switch indicating if this assembly is user defined or not.</span></span></param>
        <param name="files"><span data-ttu-id="fcb3c-110">die Liste der mit der Assembly verknüpfte Dateien</span><span class="sxs-lookup"><span data-stu-id="fcb3c-110">the list of files associated with the assembly</span></span></param>
        <param name="dependencies"><span data-ttu-id="fcb3c-111">die Liste der Abhängigkeiten im Zusammenhang mit der assembly</span><span class="sxs-lookup"><span data-stu-id="fcb3c-111">the list of dependencies associated with the assembly</span></span></param>
        <summary>
            <span data-ttu-id="fcb3c-112">Initialisiert eine neue Instanz der USqlAssembly-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-112">Initializes a new instance of the USqlAssembly class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClrName">
      <MemberSignature Language="C#" Value="public string ClrName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClrName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.ClrName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClrName As String" />
      <MemberSignature Language="F#" Value="member this.ClrName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.ClrName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clrName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-113">Ruft ab oder legt den Namen der CLR.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-113">Gets or sets the name of the CLR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.DatabaseName" />
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
            <span data-ttu-id="fcb3c-114">Ruft ab oder legt den Namen der Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-114">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dependencies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; Dependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; Dependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Dependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property Dependencies As IList(Of USqlAssemblyDependencyInfo)" />
      <MemberSignature Language="F#" Value="member this.Dependencies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Dependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyDependencyInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-115">Ruft ab oder legt die Liste der Abhängigkeiten im Zusammenhang mit der assembly</span><span class="sxs-lookup"><span data-stu-id="fcb3c-115">Gets or sets the list of dependencies associated with the assembly</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As IList(Of USqlAssemblyFileInfo)" />
      <MemberSignature Language="F#" Value="member this.Files : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-116">Ruft ab oder legt die Liste der mit der Assembly verknüpfte Dateien</span><span class="sxs-lookup"><span data-stu-id="fcb3c-116">Gets or sets the list of files associated with the assembly</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUserDefined">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUserDefined { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUserDefined" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.IsUserDefined" />
      <MemberSignature Language="VB.NET" Value="Public Property IsUserDefined As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUserDefined : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.IsUserDefined" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isUserDefined")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-117">Abrufen oder festlegen den Switch, der angibt, ob diese Assembly befindet sich eine benutzerdefinierte oder nicht.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-117">Gets or sets the switch indicating if this assembly is user defined or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsVisible">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsVisible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsVisible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.IsVisible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsVisible As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsVisible : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.IsVisible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isVisible")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-118">Ruft ab oder legt den Switch, der angibt, ob diese Assembly sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-118">Gets or sets the switch indicating if this assembly is visible or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="assemblyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcb3c-119">Ruft den Namen der Assembly ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="fcb3c-119">Gets or sets the name of the assembly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>