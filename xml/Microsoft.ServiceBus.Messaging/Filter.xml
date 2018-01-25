<Type Name="Filter" FullName="Microsoft.ServiceBus.Messaging.Filter">
  <TypeSignature Language="C#" Value="public abstract class Filter : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Filter extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Filter" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Filter&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type Filter = class&#xA;    interface IExtensibleDataObject" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="Filter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.SqlFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.TrueFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.FalseFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.CorrelationFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.DateTimeOffset))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="45d30-101">Beschreibt einen Filterausdruck, der für ein "brokeredmessage" ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="45d30-101">Describes a filter expression that is evaluated against a BrokeredMessage.</span></span></summary>
    <remarks>
            <span data-ttu-id="45d30-102">Filter ist eine abstrakte Klasse mit dem folgenden konkrete Implementierungen: <list type="bullet"> <item> <b>SqlFilter</b> , ein Filters mithilfe von SQL-Syntax darstellt. </item><item><b>CorrelationFilter</b> , der eine Optimierung für die Korrelation Gleichheitsausdrücke bereitstellt.</item></list></span><span class="sxs-lookup"><span data-stu-id="45d30-102">Filter is an abstract class with the following concrete implementations: <list type="bullet"><item><b>SqlFilter</b> that represents a filter using SQL syntax. </item><item><b>CorrelationFilter</b> that provides an optimization for correlation equality expressions.</item></list></span></span></remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.TrueFilter" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.CorrelationFilter" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" />
  </Docs>
  <Members>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public abstract bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Filter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="filter.Match message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="45d30-103">Das Objekt "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="45d30-103">The BrokeredMessage object.</span></span></param>
        <summary><span data-ttu-id="45d30-104">Entspricht der "brokeredmessage" für das FilterExpression an.</span><span class="sxs-lookup"><span data-stu-id="45d30-104">Matches the BrokeredMessage against the FilterExpression.</span></span></summary>
        <returns><span data-ttu-id="45d30-105">"true", wenn die "brokeredmessage" dem Filterausdruck entspricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="45d30-105">true if the BrokeredMessage matches the filtering expression; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="45d30-106">Der Vorgang ist mit dem aktuellen Zustand des Objekts ungültig.</span><span class="sxs-lookup"><span data-stu-id="45d30-106">The operation is invalid with the current state of object.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.FilterException"><span data-ttu-id="45d30-107">Fehler bei der Bewertung zu filtern.</span><span class="sxs-lookup"><span data-stu-id="45d30-107">Filter evaluation failed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Filter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="abstract member Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="filter.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="45d30-108">Führt eine vorverarbeitung den Filterausdruck und einer vorverarbeiteten FilterExpression zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="45d30-108">Preprocesses the filter expression and returns a preprocessed FilterExpression.</span></span></summary>
        <returns><span data-ttu-id="45d30-109">Die vorverarbeitete FilterExpression.</span><span class="sxs-lookup"><span data-stu-id="45d30-109">The preprocessed FilterExpression.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="45d30-110">Der Vorgang ist mit dem aktuellen Zustand des Objekts ungültig.</span><span class="sxs-lookup"><span data-stu-id="45d30-110">The operation is invalid with the current state of object.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public abstract bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Filter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.Filter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="45d30-111">Ruft einen Wert, der angibt, ob der Filterausdruck vorverarbeitung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="45d30-111">Gets a value indicating whether the filter expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="45d30-112">"true", wenn der Filter-Ausdruck erfordert vorverarbeitung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="45d30-112">true if the filter expression requires preprocessing; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Runtime.Serialization.IExtensibleDataObject.ExtensionData">
      <MemberSignature Language="C#" Value="System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Filter.System#Runtime#Serialization#IExtensibleDataObject#ExtensionData" />
      <MemberSignature Language="VB.NET" Value=" Property ExtensionData As ExtensionDataObject Implements IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.Messaging.Filter.System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Filter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit" Usage="filter.Validate " />
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
        <summary><span data-ttu-id="45d30-113">Überprüft das FilterExpression und sicherstellen, dass es mit der Grammatikregeln für gültige einhält.</span><span class="sxs-lookup"><span data-stu-id="45d30-113">Validates the FilterExpression and make sure it complies with the valid grammar rules.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.FilterException"><span data-ttu-id="45d30-114">Die filteranweisung ist ungültig oder wird möglicherweise komplex genug ist, um Sie zu viel rechenleistung beanspruchen beim Auswerten der Anweisung.</span><span class="sxs-lookup"><span data-stu-id="45d30-114">The filter statement is invalid or is potentially complex enough to consume too much computing power when evaluating the statement.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>