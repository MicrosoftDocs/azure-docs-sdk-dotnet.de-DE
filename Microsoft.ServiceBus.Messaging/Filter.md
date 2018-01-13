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
    <summary>Beschreibt einen Filterausdruck, der für ein "brokeredmessage" ausgewertet wird.</summary>
    <remarks>
            Filter ist eine abstrakte Klasse mit dem folgenden konkrete Implementierungen: <list type="bullet"> <item> <b>SqlFilter</b> , ein Filters mithilfe von SQL-Syntax darstellt. </item><item><b>CorrelationFilter</b> , der eine Optimierung für die Korrelation Gleichheitsausdrücke bereitstellt.</item></list></remarks>
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
        <param name="message">Das Objekt "brokeredmessage".</param>
        <summary>Entspricht der "brokeredmessage" für das FilterExpression an.</summary>
        <returns>"true", wenn die "brokeredmessage" dem Filterausdruck entspricht; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Der Vorgang ist mit dem aktuellen Zustand des Objekts ungültig.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.FilterException">Fehler bei der Bewertung zu filtern.</exception>
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
        <summary>Führt eine vorverarbeitung den Filterausdruck und einer vorverarbeiteten FilterExpression zurückgibt.</summary>
        <returns>Die vorverarbeitete FilterExpression.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Der Vorgang ist mit dem aktuellen Zustand des Objekts ungültig.</exception>
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
        <summary>Ruft einen Wert, der angibt, ob der Filterausdruck vorverarbeitung erforderlich ist.</summary>
        <value>"true", wenn der Filter-Ausdruck erfordert vorverarbeitung; andernfalls "false".</value>
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
        <summary>Überprüft das FilterExpression und sicherstellen, dass es mit der Grammatikregeln für gültige einhält.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.FilterException">Die filteranweisung ist ungültig oder wird möglicherweise komplex genug ist, um Sie zu viel rechenleistung beanspruchen beim Auswerten der Anweisung.</exception>
      </Docs>
    </Member>
  </Members>
</Type>