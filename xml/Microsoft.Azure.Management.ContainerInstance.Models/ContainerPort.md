<Type Name="ContainerPort" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort">
  <TypeSignature Language="C#" Value="public class ContainerPort" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerPort extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerPort" />
  <TypeSignature Language="F#" Value="type ContainerPort = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8eae8-101">Der Port für die Containerinstanz verfügbar gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="8eae8-101">The port exposed on the container instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8eae8-102">Initialisiert eine neue Instanz der ContainerPort-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8eae8-102">Initializes a new instance of the ContainerPort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerPort (int port, string protocol = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 port, string protocol) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.#ctor(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (port As Integer, Optional protocol As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort : int * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort (port, protocol)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="protocol" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="8eae8-103">Die Nummer des Ports innerhalb der Containergruppe verfügbar gemacht.</span><span class="sxs-lookup"><span data-stu-id="8eae8-103">The port number exposed within the container group.</span></span></param>
        <param name="protocol"><span data-ttu-id="8eae8-104">Das Protokoll der Port zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="8eae8-104">The protocol associated with the port.</span></span>
            <span data-ttu-id="8eae8-105">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="8eae8-105">Possible values include: 'TCP', 'UDP'</span></span></param>
        <summary>
            <span data-ttu-id="8eae8-106">Initialisiert eine neue Instanz der ContainerPort-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8eae8-106">Initializes a new instance of the ContainerPort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8eae8-107">Ruft ab oder legt die Portnummer, die innerhalb der Containergruppe verfügbar gemacht.</span><span class="sxs-lookup"><span data-stu-id="8eae8-107">Gets or sets the port number exposed within the container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8eae8-108">Ermittelt oder definiert das Protokoll der Port zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="8eae8-108">Gets or sets the protocol associated with the port.</span></span> <span data-ttu-id="8eae8-109">Folgende Werte sind möglich: "TCP", "UDP"</span><span class="sxs-lookup"><span data-stu-id="8eae8-109">Possible values include: 'TCP', 'UDP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerPort.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8eae8-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8eae8-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8eae8-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8eae8-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>