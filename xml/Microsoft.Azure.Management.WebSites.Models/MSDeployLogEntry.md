<Type Name="MSDeployLogEntry" FullName="Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry">
  <TypeSignature Language="C#" Value="public class MSDeployLogEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSDeployLogEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class MSDeployLogEntry" />
  <TypeSignature Language="F#" Value="type MSDeployLogEntry = class" />
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
            <span data-ttu-id="338c8-101">MSDeploy-Protokolleintrag</span><span class="sxs-lookup"><span data-stu-id="338c8-101">MSDeploy log entry</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployLogEntry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="338c8-102">Initialisiert eine neue Instanz der MSDeployLogEntry-Klasse.</span><span class="sxs-lookup"><span data-stu-id="338c8-102">Initializes a new instance of the MSDeployLogEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployLogEntry (Nullable&lt;DateTime&gt; time = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt; type = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt; type, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.#ctor(System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional time As Nullable(Of DateTime) = null, Optional type As Nullable(Of MSDeployLogEntryType) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry : Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry" Usage="new Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry (time, type, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="time"><span data-ttu-id="338c8-103">Timestamp des Protokolleintrags</span><span class="sxs-lookup"><span data-stu-id="338c8-103">Timestamp of log entry</span></span></param>
        <param name="type"><span data-ttu-id="338c8-104">Protokolleintragstyp.</span><span class="sxs-lookup"><span data-stu-id="338c8-104">Log entry type.</span></span> <span data-ttu-id="338c8-105">Folgende Werte sind möglich: "Message", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="338c8-105">Possible values include: 'Message', 'Warning', 'Error'</span></span></param>
        <param name="message"><span data-ttu-id="338c8-106">Protokolleintragsmeldung</span><span class="sxs-lookup"><span data-stu-id="338c8-106">Log entry message</span></span></param>
        <summary>
            <span data-ttu-id="338c8-107">Initialisiert eine neue Instanz der MSDeployLogEntry-Klasse.</span><span class="sxs-lookup"><span data-stu-id="338c8-107">Initializes a new instance of the MSDeployLogEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="338c8-108">Ruft protokolliert Eintrag Meldung</span><span class="sxs-lookup"><span data-stu-id="338c8-108">Gets log entry message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="338c8-109">Ruft die Zeitstempel des Protokolleintrags ab</span><span class="sxs-lookup"><span data-stu-id="338c8-109">Gets timestamp of log entry</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt; Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As Nullable(Of MSDeployLogEntryType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntryType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="338c8-110">Ruft melden Eintragstyp.</span><span class="sxs-lookup"><span data-stu-id="338c8-110">Gets log entry type.</span></span> <span data-ttu-id="338c8-111">Folgende Werte sind möglich: "Message", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="338c8-111">Possible values include: 'Message', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>