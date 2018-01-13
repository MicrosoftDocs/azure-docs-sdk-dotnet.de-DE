<Type Name="Source" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Source">
  <TypeSignature Language="C#" Value="public class Source" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Source extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Source" />
  <TypeSignature Language="VB.NET" Value="Public Class Source" />
  <TypeSignature Language="F#" Value="type Source = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5782-101">Die Registrierungsknoten, der das Ereignis generiert hat.</span><span class="sxs-lookup"><span data-stu-id="c5782-101">The registry node that generated the event.</span></span> <span data-ttu-id="c5782-102">Put unterschiedlich ist, während der Akteur das Ereignis initiiert wird, generiert die Quelle.</span><span class="sxs-lookup"><span data-stu-id="c5782-102">Put differently, while the actor initiates the event, the source generates it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Source ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Source.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c5782-103">Initialisiert eine neue Instanz der Quellklasse an.</span><span class="sxs-lookup"><span data-stu-id="c5782-103">Initializes a new instance of the Source class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Source (string addr = null, string instanceID = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string addr, string instanceID) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Source.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional addr As String = null, Optional instanceID As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Source : string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Source" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Source (addr, instanceID)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addr" Type="System.String" />
        <Parameter Name="instanceID" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addr"><span data-ttu-id="c5782-104">Die IP-Adresse oder Hostname und der Port des Registrierungs-Knotens, der das Ereignis generiert hat.</span><span class="sxs-lookup"><span data-stu-id="c5782-104">The IP or hostname and the port of the registry node that generated the event.</span></span> <span data-ttu-id="c5782-105">Dies wird im Allgemeinen durch Betriebssystem gelöst werden. HOST_NAME() zusammen mit der aktiven Port.</span><span class="sxs-lookup"><span data-stu-id="c5782-105">Generally, this will be resolved by os.Hostname() along with the running port.</span></span></param>
        <param name="instanceID"><span data-ttu-id="c5782-106">Die ausgeführte Instanz einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c5782-106">The running instance of an application.</span></span>
            <span data-ttu-id="c5782-107">Starten Sie nach jeder Änderung neu.</span><span class="sxs-lookup"><span data-stu-id="c5782-107">Changes after each restart.</span></span></param>
        <summary>
            <span data-ttu-id="c5782-108">Initialisiert eine neue Instanz der Quellklasse an.</span><span class="sxs-lookup"><span data-stu-id="c5782-108">Initializes a new instance of the Source class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addr">
      <MemberSignature Language="C#" Value="public string Addr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Addr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Source.Addr" />
      <MemberSignature Language="VB.NET" Value="Public Property Addr As String" />
      <MemberSignature Language="F#" Value="member this.Addr : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Source.Addr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5782-109">Ruft ab oder legt sie fest, die IP-Adresse oder Hostname und der Port des Registrierungs-Knotens, der das Ereignis generiert hat.</span><span class="sxs-lookup"><span data-stu-id="c5782-109">Gets or sets the IP or hostname and the port of the registry node that generated the event.</span></span> <span data-ttu-id="c5782-110">Dies wird im Allgemeinen durch Betriebssystem gelöst werden. HOST_NAME() zusammen mit der aktiven Port.</span><span class="sxs-lookup"><span data-stu-id="c5782-110">Generally, this will be resolved by os.Hostname() along with the running port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceID">
      <MemberSignature Language="C#" Value="public string InstanceID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Source.InstanceID" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceID As String" />
      <MemberSignature Language="F#" Value="member this.InstanceID : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Source.InstanceID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5782-111">Ruft ab oder legt die ausgeführte Instanz einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c5782-111">Gets or sets the running instance of an application.</span></span> <span data-ttu-id="c5782-112">Starten Sie nach jeder Änderung neu.</span><span class="sxs-lookup"><span data-stu-id="c5782-112">Changes after each restart.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>