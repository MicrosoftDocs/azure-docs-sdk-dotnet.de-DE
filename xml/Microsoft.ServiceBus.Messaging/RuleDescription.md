<Type Name="RuleDescription" FullName="Microsoft.ServiceBus.Messaging.RuleDescription">
  <TypeSignature Language="C#" Value="public sealed class RuleDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RuleDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type RuleDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RuleDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="5bb02-101">Eine Beschreibung des eine Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="5bb02-101">Represents a description of a rule.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5bb02-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />-Klasse mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="5bb02-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> class with default values.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription filter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="5bb02-103">Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-103">The filter expression used to match messages.</span></span></param>
        <summary><span data-ttu-id="5bb02-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> Klasse mit dem angegebenen Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="5bb02-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> class with the specified filter expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : string -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5bb02-105">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="5bb02-105">The name of the rule.</span></span></param>
        <summary><span data-ttu-id="5bb02-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />-Klasse mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> class with the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : string * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription (name, filter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5bb02-107">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="5bb02-107">The name of the rule.</span></span></param>
        <param name="filter"><span data-ttu-id="5bb02-108">Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-108">The filter expression used to match messages.</span></span></param>
        <summary><span data-ttu-id="5bb02-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> Klasse mit dem angegebenen Namen und die Filter-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="5bb02-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> class with the specified name and filter expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RuleAction Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.RuleAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As RuleAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceBus.Messaging.RuleAction with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Action", Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RuleAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5bb02-110">Ruft ab oder legt fest, die Aktion ausführen, wenn die Nachricht der Filterausdruck erfüllt.</span><span class="sxs-lookup"><span data-stu-id="5bb02-110">Gets or sets the action to perform if the message satisfies the filtering expression.</span></span></summary>
        <value><span data-ttu-id="5bb02-111">Die Aktion ausführen, wenn die Nachricht der Filterausdruck erfüllt.</span><span class="sxs-lookup"><span data-stu-id="5bb02-111">The action to perform if the message satisfies the filtering expression.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5bb02-112">Ruft die Erstellungszeit der Regel ab.</span><span class="sxs-lookup"><span data-stu-id="5bb02-112">Gets creation time of the rule.</span></span></summary>
        <value><span data-ttu-id="5bb02-113">Der Zeitpunkt der Erstellung der Regel.</span><span class="sxs-lookup"><span data-stu-id="5bb02-113">The creation time of the rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultRuleName : string" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bb02-114">Der Standardname Erstellung Standardregel beim Hinzufügen von Abonnements zu einem Thema verwendet.</span><span class="sxs-lookup"><span data-stu-id="5bb02-114">The default name used in creating default rule when adding subscriptions to a topic.</span></span> <span data-ttu-id="5bb02-115">Der Name ist "$Default".</span><span class="sxs-lookup"><span data-stu-id="5bb02-115">The name is "$Default".</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Filter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Filter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As Filter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.ServiceBus.Messaging.Filter with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Filter", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5bb02-116">Ruft ab oder legt den Filterausdruck verwendet, um Nachrichten zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-116">Gets or sets the filter expression used to match messages.</span></span></summary>
        <value><span data-ttu-id="5bb02-117">Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-117">The filter expression used to match messages.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5bb02-118">Null (Nothing in Visual Basic) zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="5bb02-118">null (Nothing in Visual Basic) is assigned.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Name", Order=131077)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5bb02-119">Ruft ab oder legt den Namen der Regel.</span><span class="sxs-lookup"><span data-stu-id="5bb02-119">Gets or sets the name of the rule.</span></span></summary>
        <value><span data-ttu-id="5bb02-120">Gibt eine <see cref="T:System.String" /> , die den Namen der Regel.</span><span class="sxs-lookup"><span data-stu-id="5bb02-120">Returns a <see cref="T:System.String" /> Representing the name of the rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>