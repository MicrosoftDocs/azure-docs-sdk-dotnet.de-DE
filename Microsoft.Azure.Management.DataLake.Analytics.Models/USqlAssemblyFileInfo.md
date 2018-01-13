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
            Ein Data Lake Analytics U-SQL-Assembly Datei Informationen Katalogelement.
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
            Initialisiert eine neue Instanz der USqlAssemblyFileInfo-Klasse.
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
        <param name="type">der Dateityp für die Assembly. Folgende Werte sind möglich: "Assembly", "Resource", "Nodeploy"</param>
        <param name="originalPath">das der ursprüngliche Pfad der Assemblydatei.</param>
        <param name="contentPath">der der Pfad der Assemblydatei.</param>
        <summary>
            Initialisiert eine neue Instanz der USqlAssemblyFileInfo-Klasse.
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
            Ruft ab oder legt den der Pfad der Assemblydatei.
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
            Ruft ab oder legt die den ursprünglichen Pfad der Assemblydatei.
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
            Ruft ab oder legt die Assembly Dateityp. Folgende Werte sind möglich: "Assembly", "Resource", "Nodeploy"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>