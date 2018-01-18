<Type Name="FileSystemApplicationLogsConfig" FullName="Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class FileSystemApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type FileSystemApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6fcea-101">Anwendungsprotokolle, Konfiguration des Dateisystems.</span><span class="sxs-lookup"><span data-stu-id="6fcea-101">Application logs to file system configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6fcea-102">Initialisiert eine neue Instanz der FileSystemApplicationLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6fcea-102">Initializes a new instance of the FileSystemApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemApplicationLogsConfig (Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; level = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; level) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig.#ctor(System.Nullable{Microsoft.Azure.Management.WebSites.Models.LogLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional level As Nullable(Of LogLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig" Usage="new Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig level" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="6fcea-103">Protokollebene.</span><span class="sxs-lookup"><span data-stu-id="6fcea-103">Log level.</span></span> <span data-ttu-id="6fcea-104">Folgende Werte sind möglich: "Off", "Verbose", "Information", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="6fcea-104">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span></param>
        <summary>
            <span data-ttu-id="6fcea-105">Initialisiert eine neue Instanz der FileSystemApplicationLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6fcea-105">Initializes a new instance of the FileSystemApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FileSystemApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcea-106">Ruft ab, oder legt ihn fest Protokollebene.</span><span class="sxs-lookup"><span data-stu-id="6fcea-106">Gets or sets log level.</span></span> <span data-ttu-id="6fcea-107">Folgende Werte sind möglich: "Off", "Verbose", "Information", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="6fcea-107">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>