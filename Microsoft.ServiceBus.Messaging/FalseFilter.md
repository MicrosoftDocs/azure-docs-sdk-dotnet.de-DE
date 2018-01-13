<Type Name="FalseFilter" FullName="Microsoft.ServiceBus.Messaging.FalseFilter">
  <TypeSignature Language="C#" Value="public sealed class FalseFilter : Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FalseFilter extends Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.FalseFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FalseFilter&#xA;Inherits SqlFilter" />
  <TypeSignature Language="F#" Value="type FalseFilter = class&#xA;    inherit SqlFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.SqlFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="FalseFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt den Filterausdruck "false".</summary>
    <remarks>Der Ausdruck Übereinstimmung keine sollte verwendet werden, wenn Sie ein Abonnement, das anfänglich alle Nachrichten blockieren erstellen möchten. In der Regel ist in diesem Szenario sollten Sie das Abonnement erstellen, aber dieses Abonnement zu einem späteren Zeitpunkt aktivieren möchten. Dieser Filter wird dieses Szenario zu ermöglichen. </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FalseFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="falseFilter.Match message" />
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
        <param name="message">Die vermittelte Nachricht.</param>
        <summary>Entspricht eine Nachricht anhand der aktuellen SQL-Ausdruck.</summary>
        <returns>"true", sofern es entspricht; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="falseFilter.Preprocess " />
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
        <summary>Ruft den vorverarbeiteten Filterausdruck an.</summary>
        <returns>Der Filterausdruck vorverarbeitet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der angibt, ob die SQL-Filterausdruck vorverarbeitung erforderlich ist.</summary>
        <value>"true", wenn die SQL Ausdruck filtern muss vorverarbeitung; andernfalls "false". Gibt zurzeit immer "true" zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="falseFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Konvertiert die aktuelle Instanz in die Zeichenfolgendarstellung.</summary>
        <returns>Eine Zeichenfolgendarstellung der aktuellen Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="falseFilter.Validate " />
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
        <summary>Überprüft die SQL-Ausdruck.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>