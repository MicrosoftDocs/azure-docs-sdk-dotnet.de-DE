<Type Name="AdmRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.AdmRegistrationDescription">
  <TypeSignature Language="C#" Value="public class AdmRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdmRegistrationDescription extends Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class AdmRegistrationDescription&#xA;Inherits RegistrationDescription" />
  <TypeSignature Language="F#" Value="type AdmRegistrationDescription = class&#xA;    inherit RegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AdmRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="61347-101">Stellt die Beschreibung der Amazon Device Messaging (ADM) Registrierung.</span><span class="sxs-lookup"><span data-stu-id="61347-101">Represents the description of the Amazon Device Messaging (ADM) registration.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmRegistrationDescription (Microsoft.Azure.NotificationHubs.AdmRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.AdmRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription : Microsoft.Azure.NotificationHubs.AdmRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration"><span data-ttu-id="61347-102">Die Quell-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="61347-102">The source registration.</span></span></param>
        <summary><span data-ttu-id="61347-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61347-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmRegistrationDescription (string admRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string admRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (admRegistrationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription : string -&gt; Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription admRegistrationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="61347-104">Amazon Device Messaging registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="61347-104">The Amazon Device Messaging registration identifier.</span></span></param>
        <summary><span data-ttu-id="61347-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61347-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmRegistrationDescription (string admRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string admRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (admRegistrationId As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription : string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AdmRegistrationDescription (admRegistrationId, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="61347-106">Amazon Device Messaging registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="61347-106">The Amazon Device Messaging registration identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="61347-107">Die Registrierung-Tags.</span><span class="sxs-lookup"><span data-stu-id="61347-107">The registration tags.</span></span></param>
        <summary><span data-ttu-id="61347-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61347-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdmRegistrationId">
      <MemberSignature Language="C#" Value="public string AdmRegistrationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdmRegistrationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmRegistrationDescription.AdmRegistrationId" />
      <MemberSignature Language="VB.NET" Value="Public Property AdmRegistrationId As String" />
      <MemberSignature Language="F#" Value="member this.AdmRegistrationId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmRegistrationDescription.AdmRegistrationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="AdmRegistrationId", Order=2001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61347-109">Abrufen oder Festlegen der Amazon Device Messaging-registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="61347-109">Gets or sets the Amazon Device Messaging registration identifier.</span></span></summary>
        <value><span data-ttu-id="61347-110">Amazon Device Messaging registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="61347-110">The Amazon Device Messaging registration identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>