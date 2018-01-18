<Type Name="PerfMonResponse" FullName="Microsoft.Azure.Management.WebSites.Models.PerfMonResponse">
  <TypeSignature Language="C#" Value="public class PerfMonResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PerfMonResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class PerfMonResponse" />
  <TypeSignature Language="F#" Value="type PerfMonResponse = class" />
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
            <span data-ttu-id="70f89-101">Performance Monitor-API-Antwort.</span><span class="sxs-lookup"><span data-stu-id="70f89-101">Performance monitor API response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70f89-102">Initialisiert eine neue Instanz der PerfMonResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70f89-102">Initializes a new instance of the PerfMonResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonResponse (string code = null, string message = null, Microsoft.Azure.Management.WebSites.Models.PerfMonSet data = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class Microsoft.Azure.Management.WebSites.Models.PerfMonSet data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.#ctor(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.PerfMonSet)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional data As PerfMonSet = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PerfMonResponse : string * string * Microsoft.Azure.Management.WebSites.Models.PerfMonSet -&gt; Microsoft.Azure.Management.WebSites.Models.PerfMonResponse" Usage="new Microsoft.Azure.Management.WebSites.Models.PerfMonResponse (code, message, data)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="data" Type="Microsoft.Azure.Management.WebSites.Models.PerfMonSet" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="70f89-103">Der Antwortcode.</span><span class="sxs-lookup"><span data-stu-id="70f89-103">The response code.</span></span></param>
        <param name="message"><span data-ttu-id="70f89-104">Die Meldung.</span><span class="sxs-lookup"><span data-stu-id="70f89-104">The message.</span></span></param>
        <param name="data"><span data-ttu-id="70f89-105">Die Leistungsindikatoren des Systemmonitors.</span><span class="sxs-lookup"><span data-stu-id="70f89-105">The performance monitor counters.</span></span></param>
        <summary>
            <span data-ttu-id="70f89-106">Initialisiert eine neue Instanz der PerfMonResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70f89-106">Initializes a new instance of the PerfMonResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70f89-107">Ruft ab oder legt den Antwortcode.</span><span class="sxs-lookup"><span data-stu-id="70f89-107">Gets or sets the response code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.PerfMonSet Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.PerfMonSet Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As PerfMonSet" />
      <MemberSignature Language="F#" Value="member this.Data : Microsoft.Azure.Management.WebSites.Models.PerfMonSet with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.PerfMonSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70f89-108">Ruft ab oder legt die Leistung Systemmonitor-Leistungsindikatoren.</span><span class="sxs-lookup"><span data-stu-id="70f89-108">Gets or sets the performance monitor counters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonResponse.Message" />
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
            <span data-ttu-id="70f89-109">Ruft ab oder legt die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="70f89-109">Gets or sets the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>