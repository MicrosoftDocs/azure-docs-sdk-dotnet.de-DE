<Type Name="USqlAssemblyFileInfo" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo">
  <TypeSignature Language="C#" Value="public class USqlAssemblyFileInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlAssemblyFileInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlAssemblyFileInfo" />
  <TypeSignature Language="F#" Value="type USqlAssemblyFileInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29a5c-101">Ein Data Lake Analytics U-SQL-Assembly Datei Informationen Katalogelement.</span><span class="sxs-lookup"><span data-stu-id="29a5c-101">A Data Lake Analytics catalog U-SQL assembly file information item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssemblyFileInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29a5c-102">Initialisiert eine neue Instanz der USqlAssemblyFileInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29a5c-102">Initializes a new instance of the USqlAssemblyFileInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssemblyFileInfo (string type = null, string originalPath = null, string contentPath = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string originalPath, string contentPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional originalPath As String = null, Optional contentPath As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo : string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo (type, originalPath, contentPath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="originalPath" Type="System.String" />
        <Parameter Name="contentPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="29a5c-103">der Dateityp für die Assembly.</span><span class="sxs-lookup"><span data-stu-id="29a5c-103">the assembly file type.</span></span> <span data-ttu-id="29a5c-104">Folgende Werte sind möglich: "Assembly", "Resource", "Nodeploy"</span><span class="sxs-lookup"><span data-stu-id="29a5c-104">Possible values include: 'Assembly', 'Resource', 'Nodeploy'</span></span></param>
        <param name="originalPath"><span data-ttu-id="29a5c-105">das der ursprüngliche Pfad der Assemblydatei.</span><span class="sxs-lookup"><span data-stu-id="29a5c-105">the the original path to the assembly file.</span></span></param>
        <param name="contentPath"><span data-ttu-id="29a5c-106">der der Pfad der Assemblydatei.</span><span class="sxs-lookup"><span data-stu-id="29a5c-106">the the content path to the assembly file.</span></span></param>
        <summary>
            <span data-ttu-id="29a5c-107">Initialisiert eine neue Instanz der USqlAssemblyFileInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29a5c-107">Initializes a new instance of the USqlAssemblyFileInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentPath">
      <MemberSignature Language="C#" Value="public string ContentPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.ContentPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentPath As String" />
      <MemberSignature Language="F#" Value="member this.ContentPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.ContentPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29a5c-108">Ruft ab oder legt den der Pfad der Assemblydatei.</span><span class="sxs-lookup"><span data-stu-id="29a5c-108">Gets or sets the the content path to the assembly file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalPath">
      <MemberSignature Language="C#" Value="public string OriginalPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginalPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.OriginalPath" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginalPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.OriginalPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="originalPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29a5c-109">Ruft ab oder legt die den ursprünglichen Pfad der Assemblydatei.</span><span class="sxs-lookup"><span data-stu-id="29a5c-109">Gets or sets the the original path to the assembly file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyFileInfo.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29a5c-110">Ruft ab oder legt die Assembly Dateityp.</span><span class="sxs-lookup"><span data-stu-id="29a5c-110">Gets or sets the assembly file type.</span></span> <span data-ttu-id="29a5c-111">Folgende Werte sind möglich: "Assembly", "Resource", "Nodeploy"</span><span class="sxs-lookup"><span data-stu-id="29a5c-111">Possible values include: 'Assembly', 'Resource', 'Nodeploy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>