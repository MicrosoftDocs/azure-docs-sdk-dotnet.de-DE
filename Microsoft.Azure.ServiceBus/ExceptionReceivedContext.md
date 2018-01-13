<Type Name="ExceptionReceivedContext" FullName="Microsoft.Azure.ServiceBus.ExceptionReceivedContext">
  <TypeSignature Language="C#" Value="public class ExceptionReceivedContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExceptionReceivedContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" />
  <TypeSignature Language="VB.NET" Value="Public Class ExceptionReceivedContext" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Kontext für <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> vom Client ausgelöste Ausnahme.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedContext (string action, string endpoint, string entityPath, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string action, string endpoint, string entityPath, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As String, endpoint As String, entityPath As String, clientId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ExceptionReceivedContext : string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ExceptionReceivedContext" Usage="new Microsoft.Azure.ServiceBus.ExceptionReceivedContext (action, endpoint, entityPath, clientId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="action">Die Aktion, die der Ausnahme zugeordnet ist.</param>
        <param name="endpoint">Der Endpunkt der Ausnahme zugeordnet ist.</param>
        <param name="entityPath">Der Entity-Pfad der Ausnahme zugeordnet ist.</param>
        <param name="clientId">Die Client-Id kann zum Zuordnen der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />, <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />, <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" /> oder <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> , die die Ausnahme ist aufgetreten.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Aktion, die dem Ereignis zugeordnet.</summary>
        <value>Die Aktion, die dem Ereignis zugeordnet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Die Client-Id zugeordnet, den Absender, Empfänger oder Sitzung, wenn diese Ausnahme aufgetreten ist.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Der Namespacename verwendet, wenn diese Ausnahme aufgetreten ist.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Der Entity-Pfad verwendet, wenn diese Ausnahme aufgetreten ist.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>