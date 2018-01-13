<Type Name="RemoteLoginInformation" FullName="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation">
  <TypeSignature Language="C#" Value="public class RemoteLoginInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RemoteLoginInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class RemoteLoginInformation" />
  <TypeSignature Language="F#" Value="type RemoteLoginInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c839f-101">Enthält Details der Remoteanmeldung SSH/RDP auf einen Serverknoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="c839f-101">Contains remote login details to SSH/RDP to a compute node in cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteLoginInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c839f-102">Initialisiert eine neue Instanz der RemoteLoginInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c839f-102">Initializes a new instance of the RemoteLoginInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteLoginInformation (string nodeId, string ipAddress, double port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeId, string ipAddress, float64 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.#ctor(System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeId As String, ipAddress As String, port As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation : string * string * double -&gt; Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation" Usage="new Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation (nodeId, ipAddress, port)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="port" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="nodeId"><span data-ttu-id="c839f-103">ID des Serverknotens</span><span class="sxs-lookup"><span data-stu-id="c839f-103">Id of the compute node</span></span></param>
        <param name="ipAddress"><span data-ttu-id="c839f-104">IP-Adresse</span><span class="sxs-lookup"><span data-stu-id="c839f-104">ip address</span></span></param>
        <param name="port"><span data-ttu-id="c839f-105">Portnummer</span><span class="sxs-lookup"><span data-stu-id="c839f-105">port number</span></span></param>
        <summary>
            <span data-ttu-id="c839f-106">Initialisiert eine neue Instanz der RemoteLoginInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c839f-106">Initializes a new instance of the RemoteLoginInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c839f-107">Ruft ab oder legt die IP-Adresse</span><span class="sxs-lookup"><span data-stu-id="c839f-107">Gets or sets ip address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c839f-108">Ruft ab oder legt die Id des Serverknotens</span><span class="sxs-lookup"><span data-stu-id="c839f-108">Gets or sets id of the compute node</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public double Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Double" />
      <MemberSignature Language="F#" Value="member this.Port : double with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c839f-109">Ruft ab oder legt die Portnummer fest</span><span class="sxs-lookup"><span data-stu-id="c839f-109">Gets or sets port number</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="remoteLoginInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c839f-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c839f-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c839f-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c839f-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>