<Type Name="RuleAction" FullName="Microsoft.ServiceBus.Messaging.RuleAction">
  <TypeSignature Language="C#" Value="public abstract class RuleAction : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RuleAction extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RuleAction&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type RuleAction = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RuleAction", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.EmptyRuleAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.SqlRuleAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.CompositeAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.RuleCreationAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.DateTimeOffset))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="190d6-101">Stellt Filteraktionen, die zulässig sind, für die Transformation einer Nachricht, die von einem Filterausdruck abgeglichen wurden.</span><span class="sxs-lookup"><span data-stu-id="190d6-101">Represents the filter actions which are allowed for the transformation of a message that have been matched by a filter expression.</span></span></summary>
    <remarks>
            <span data-ttu-id="190d6-102">Filteraktionen auf ermöglichen die Transformation einer Nachricht, die von einem Filterausdruck abgeglichen wurden.</span><span class="sxs-lookup"><span data-stu-id="190d6-102">Filter actions allow for the transformation of a message that have been matched by a filter expression.</span></span> <span data-ttu-id="190d6-103">Der typischer Anwendungsfall für Filter Acions wird angefügt oder Aktualisieren der Eigenschaften, die eine Nachricht, z. B. zuweisen eine Gruppen-ID, die basierend auf einer Nachricht die Korrelations-ID zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="190d6-103">The typical use case for filter acions is to append or update the properties that are attached to a message, for example assigning a group ID based on the correlation ID of a message.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.EmptyRuleAction" />
  </Docs>
  <Members>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.Messaging.BrokeredMessage Execute (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Execute(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Execute(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Execute (message As BrokeredMessage) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="ruleAction.Execute message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="190d6-104">Geben Sie "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="190d6-104">Input BrokeredMessage.</span></span></param>
        <summary><span data-ttu-id="190d6-105">Führt die Filteraktion für die angegebene "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="190d6-105">Executes the filter action on the supplied BrokeredMessage.</span></span></summary>
        <returns><span data-ttu-id="190d6-106">Die Änderung nach der Ausführung der Regelaktion "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="190d6-106">The modified BrokeredMessage after executing the rule action.</span></span></returns>
        <remarks><span data-ttu-id="190d6-107">Konkrete Implementierung dieser Klasse ist "InvalidOperationException" auslösen kann nach Belieben ist dies die vorverarbeitung erfordert.</span><span class="sxs-lookup"><span data-stu-id="190d6-107">Concrete implementation of this class is free to throw InvalidOperationException is this requires preprocessing.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.Messaging.RuleAction Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.RuleAction Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Preprocess () As RuleAction" />
      <MemberSignature Language="F#" Value="abstract member Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.RuleAction" Usage="ruleAction.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RuleAction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="190d6-108">Führt eine vorverarbeitung der <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="190d6-108">Preprocesses the <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> object.</span></span></summary>
        <returns><span data-ttu-id="190d6-109">Die vorverarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="190d6-109">The preprocessed <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> object.</span></span></returns>
        <remarks><span data-ttu-id="190d6-110">Konkrete Implementierung dieser Klasse ist "InvalidOperationException" auslösen kann nach Belieben ist dies die vorverarbeitung erfordert.</span><span class="sxs-lookup"><span data-stu-id="190d6-110">Concrete implementation of this class is free to throw InvalidOperationException is this requires preprocessing.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public abstract bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleAction.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.RuleAction.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="190d6-111">Ruft einen Wert, der angibt, ob die Aktion für eine vorverarbeitung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="190d6-111">Gets a value that indicates whether the rule action requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="190d6-112">"true", wenn die Regelaktion erfordert vorverarbeitung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="190d6-112">true if the rule action requires preprocessing; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Runtime.Serialization.IExtensibleDataObject.ExtensionData">
      <MemberSignature Language="C#" Value="System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleAction.System#Runtime#Serialization#IExtensibleDataObject#ExtensionData" />
      <MemberSignature Language="VB.NET" Value=" Property ExtensionData As ExtensionDataObject Implements IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.Messaging.RuleAction.System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public abstract void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit" Usage="ruleAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="190d6-113">Überprüft die Regelaktion der Grammatik.</span><span class="sxs-lookup"><span data-stu-id="190d6-113">Validates the rule action against the grammar.</span></span> </summary>
        <remarks><span data-ttu-id="190d6-114">Konkrete Implementierung dieser Klasse ist "InvalidOperationException" auslösen kann nach Belieben ist dies die vorverarbeitung erfordert.</span><span class="sxs-lookup"><span data-stu-id="190d6-114">Concrete implementation of this class is free to throw InvalidOperationException is this requires preprocessing.</span></span></remarks>
        <altmember cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
      </Docs>
    </Member>
  </Members>
</Type>