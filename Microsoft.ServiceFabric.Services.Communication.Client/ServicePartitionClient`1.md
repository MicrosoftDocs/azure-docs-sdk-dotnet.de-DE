<Type Name="ServicePartitionClient&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public class ServicePartitionClient&lt;TCommunicationClient&gt; : Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionClient`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1&lt;!TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionClient(Of TCommunicationClient)&#xA;Implements IServicePartitionClient(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    interface IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;TCommunicationClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TCommunicationClient">Kommunikation-Clienttyp</typeparam>
    <summary>
            Gibt eine Instanz der Kommunikation zwischen Client, der kommunizieren kann mit den Replikaten einer bestimmten Partition an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionClient (Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; communicationClientFactory, Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey = null, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector = Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica, string listenerName = null, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt; communicationClientFactory, class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory{`0},System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; (communicationClientFactory, serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="communicationClientFactory" Type="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;" />
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="communicationClientFactory">Client-Kommunikation-factory</param>
        <param name="serviceUri">Name des Diensts</param>
        <param name="partitionKey">Der Partitionsschlüssel verwendet, um die Partition in den Dienst zu identifizieren.</param>
        <param name="targetReplicaSelector">Informationen zum Replikat</param>
        <param name="listenerName">Listener im Replikat, zu dem der Client eine eine Verbindung herstellen soll</param>
        <param name="retrySettings">Wiederholungsrichtlinie für Ausnahmen, die während der Kommunikation angezeigt</param>
        <summary>
            Instanziiert einen Dienstclient für die Partition, der die angegebene Client-Factory verwendet, erstellen Sie einen Client zum Kommunizieren mit den Dienstendpunkt, der durch den Dienst-Uri, Partitionkey, Replikat und Listener Argumente identifiziert verwendet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Factory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; Factory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt; Factory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.Factory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Factory As ICommunicationClientFactory(Of TCommunicationClient)" />
      <MemberSignature Language="F#" Value="member this.Factory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.Factory" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.Factory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Kommunikation zwischen Client Factory ab
            </summary>
        <value>Client-Kommunikation-factory</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetry">
      <MemberSignature Language="C#" Value="public void InvokeWithRetry (Action&lt;TCommunicationClient&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InvokeWithRetry(class System.Action`1&lt;!TCommunicationClient&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetry(System.Action{`0},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub InvokeWithRetry (func As Action(Of TCommunicationClient), ParamArray doNotRetryExceptionTypes As Type())" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetry : Action&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; unit" Usage="servicePartitionClient.InvokeWithRetry (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Action&lt;TCommunicationClient&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetry&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public TResult InvokeWithRetry&lt;TResult&gt; (Func&lt;TCommunicationClient,TResult&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!TResult InvokeWithRetry&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, !!TResult&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetry``1(System.Func{`0,``0},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetry(Of TResult) (func As Func(Of TCommunicationClient, TResult), ParamArray doNotRetryExceptionTypes As Type()) As TResult" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetry : Func&lt;'CommunicationClient, 'Result (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; 'Result" Usage="servicePartitionClient.InvokeWithRetry (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,TResult&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult">Führen Sie von der aufgerufenen Funktion</typeparam>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <returns>Die Funktion, die im Argument angegebene Optimierungsfehler</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InvokeWithRetryAsync (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task InvokeWithRetryAsync(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync(System.Func{`0,System.Threading.Tasks.Task},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetryAsync (func As Func(Of TCommunicationClient, Task), ParamArray doNotRetryExceptionTypes As Type()) As Task" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; System.Threading.Tasks.Task" Usage="servicePartitionClient.InvokeWithRetryAsync (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InvokeWithRetryAsync (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt; func, System.Threading.CancellationToken cancellationToken, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task InvokeWithRetryAsync(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task&gt; func, valuetype System.Threading.CancellationToken cancellationToken, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync(System.Func{`0,System.Threading.Tasks.Task},System.Threading.CancellationToken,System.Type[])" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * System.Threading.CancellationToken * Type[] -&gt; System.Threading.Tasks.Task" Usage="servicePartitionClient.InvokeWithRetryAsync (func, cancellationToken, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResult&gt; InvokeWithRetryAsync&lt;TResult&gt; (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt; func, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TResult&gt; InvokeWithRetryAsync&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; func, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync``1(System.Func{`0,System.Threading.Tasks.Task{``0}},System.Type[])" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeWithRetryAsync(Of TResult) (func As Func(Of TCommunicationClient, Task(Of TResult)), ParamArray doNotRetryExceptionTypes As Type()) As Task(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task&lt;'Result&gt; (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * Type[] -&gt; System.Threading.Tasks.Task&lt;'Result&gt;" Usage="servicePartitionClient.InvokeWithRetryAsync (func, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__23`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt;" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult">Führen Sie von der aufgerufenen Funktion</typeparam>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist das Ergebnis von der Funktion im Argument angegeben.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeWithRetryAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResult&gt; InvokeWithRetryAsync&lt;TResult&gt; (Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt; func, System.Threading.CancellationToken cancellationToken, params Type[] doNotRetryExceptionTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TResult&gt; InvokeWithRetryAsync&lt;TResult&gt;(class System.Func`2&lt;!TCommunicationClient, class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; func, valuetype System.Threading.CancellationToken cancellationToken, class System.Type[] doNotRetryExceptionTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.InvokeWithRetryAsync``1(System.Func{`0,System.Threading.Tasks.Task{``0}},System.Threading.CancellationToken,System.Type[])" />
      <MemberSignature Language="F#" Value="member this.InvokeWithRetryAsync : Func&lt;'CommunicationClient, System.Threading.Tasks.Task&lt;'Result&gt; (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; * System.Threading.CancellationToken * Type[] -&gt; System.Threading.Tasks.Task&lt;'Result&gt;" Usage="servicePartitionClient.InvokeWithRetryAsync (func, cancellationToken, doNotRetryExceptionTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1/&lt;InvokeWithRetryAsync&gt;d__24`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TCommunicationClient,System.Threading.Tasks.Task&lt;TResult&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="doNotRetryExceptionTypes" Type="System.Type[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TResult">Führen Sie von der aufgerufenen Funktion</typeparam>
        <param name="func">Die aufgerufene Funktion</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <param name="doNotRetryExceptionTypes">Ausnahmen, die für die der Dienstclient für die Partition nicht den wiederholen soll</param>
        <summary>
            Ruft die angegebene Funktion auf, und wiederholen Sie dann für andere als die Ausnahmen in der DoNotRetryExceptionTypes ausgelösten Ausnahmen.
            Ausnahmen, die nicht in DoNotRetryExceptionTypes enthalten sind, steuert CommunicationClientFactorys ReportOperationExceptionAsync()-Methode, wenn die Ausnahme oder nicht wiederholt werden soll.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist das Ergebnis von der Funktion im Argument angegeben.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ListenerName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ListenerName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Listeners im Replikat, zu dem der Client eine eine Verbindung herstellen soll.
            </summary>
        <value>Name des Listeners</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As ServicePartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.PartitionKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Partitionsschlüssel ab.
            </summary>
        <value>Partitionsschlüssel</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ServiceUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Diensts ab
            </summary>
        <value>Name des Diensts</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSelector">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.TargetReplicaSelector" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplicaSelector As TargetReplicaSelector" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSelector : Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TargetReplicaSelector" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TargetReplicaSelector</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Informationen über welches, der Replikat in der Partition der Client eine eine Verbindung herstellen soll.
            </summary>
        <value>Eine <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" /></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetLastResolvedServicePartition">
      <MemberSignature Language="C#" Value="public bool TryGetLastResolvedServicePartition (out System.Fabric.ResolvedServicePartition resolvedServicePartition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetLastResolvedServicePartition([out] class System.Fabric.ResolvedServicePartition&amp; resolvedServicePartition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ServicePartitionClient`1.TryGetLastResolvedServicePartition(System.Fabric.ResolvedServicePartition@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetLastResolvedServicePartition (ByRef resolvedServicePartition As ResolvedServicePartition) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetLastResolvedServicePartition :  -&gt; bool&#xA;override this.TryGetLastResolvedServicePartition :  -&gt; bool" Usage="servicePartitionClient.TryGetLastResolvedServicePartition resolvedServicePartition" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TryGetLastResolvedServicePartition(System.Fabric.ResolvedServicePartition@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resolvedServicePartition" Type="System.Fabric.ResolvedServicePartition&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="resolvedServicePartition">Vorherige ResolvedServicePartition</param>
        <summary>
            Ruft den aufgelösten Dienstpartition, der auf dem Client festgelegt wurde.
            </summary>
        <returns>True, wenn eine ResolvedServicePartition wurde festgelegt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>