<Type Name="ClientEntity" FullName="Microsoft.ServiceBus.Messaging.ClientEntity">
  <TypeSignature Language="C#" Value="public abstract class ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ClientEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ClientEntity" />
  <TypeSignature Language="F#" Value="type ClientEntity = class&#xA;    interface IMessageClientEntity&#xA;    interface ICloseable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Eine Datenstruktur, die die Ereignisse von einem Datenstrom Event Hub gesendete und empfangene darstellt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public virtual void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="clientEntity.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageClientEntity.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Führt Funktionen für Abbruch der messaging-Entität.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="public void Close ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Close() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.Close" />
      <MemberSignature Language="VB.NET" Value="Public Sub Close ()" />
      <MemberSignature Language="F#" Value="abstract member Close : unit -&gt; unit&#xA;override this.Close : unit -&gt; unit" Usage="clientEntity.Close " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageClientEntity.Close</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Sendet eine Bereinigung-Nachricht an Service Bus, um den Abschluss der Verwendung einer Entität zu signalisieren.</summary>
        <remarks>Im Fall von Ausnahmen führt die Methode einen Abbruch auf die Entität vor dem Auslösen der Ausnahme.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clientEntity.CloseAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageClientEntity.CloseAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Sendet eine Nachricht Cleanup asynchron in Service Bus, um den Abschluss der Verwendung einer Entität zu signalisieren.</summary>
        <returns>Wenn eine Ausnahme auftritt, führt diese Methode ein Abbruchvorgang für die Entität vor dem Auslösen der Ausnahme.</returns>
        <remarks>Im Fall von Ausnahmen führt die Methode einen Abbruch auf die Entität vor dem Auslösen der Ausnahme.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fault">
      <MemberSignature Language="C#" Value="protected void Fault ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Fault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.Fault" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Fault ()" />
      <MemberSignature Language="F#" Value="member this.Fault : unit -&gt; unit" Usage="clientEntity.Fault " />
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
        <summary>Nur zur internen Verwendung. Nicht von dieser Klasse erben.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~ClientEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="clientEntity.Finalize " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsClosed">
      <MemberSignature Language="C#" Value="public bool IsClosed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsClosed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ClientEntity.IsClosed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsClosed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsClosed : bool" Usage="Microsoft.ServiceBus.Messaging.ClientEntity.IsClosed" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IMessageClientEntity.IsClosed</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>Gibt <see cref="T:System.Boolean" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected abstract void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit" Usage="clientEntity.OnAbort " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="clientEntity.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary />
        <returns>Gibt <see cref="T:System.IAsyncResult" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="clientEntity.OnBeginOpen (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary />
        <returns>Gibt <see cref="T:System.IAsyncResult" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected virtual void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnClose : TimeSpan -&gt; unit&#xA;override this.OnClose : TimeSpan -&gt; unit" Usage="clientEntity.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosed">
      <MemberSignature Language="C#" Value="protected virtual void OnClosed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnClosed() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnClosed" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnClosed ()" />
      <MemberSignature Language="F#" Value="abstract member OnClosed : unit -&gt; unit&#xA;override this.OnClosed : unit -&gt; unit" Usage="clientEntity.OnClosed " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected abstract void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndClose : IAsyncResult -&gt; unit" Usage="clientEntity.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected abstract void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndOpen : IAsyncResult -&gt; unit" Usage="clientEntity.OnEndOpen result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnFaulted">
      <MemberSignature Language="C#" Value="protected virtual void OnFaulted ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnFaulted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnFaulted" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnFaulted ()" />
      <MemberSignature Language="F#" Value="abstract member OnFaulted : unit -&gt; unit&#xA;override this.OnFaulted : unit -&gt; unit" Usage="clientEntity.OnFaulted " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpen">
      <MemberSignature Language="C#" Value="protected virtual void OnOpen (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnOpen(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnOpen : TimeSpan -&gt; unit&#xA;override this.OnOpen : TimeSpan -&gt; unit" Usage="clientEntity.OnOpen timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpened">
      <MemberSignature Language="C#" Value="protected virtual void OnOpened ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnOpened() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.OnOpened" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnOpened ()" />
      <MemberSignature Language="F#" Value="abstract member OnOpened : unit -&gt; unit&#xA;override this.OnOpened : unit -&gt; unit" Usage="clientEntity.OnOpened " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ClientEntity.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.ServiceBus.RetryPolicy with get, set" Usage="Microsoft.ServiceBus.Messaging.ClientEntity.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>Gibt <see cref="T:Microsoft.ServiceBus.RetryPolicy" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ClientEntity.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.ServiceBus.Messaging.ClientEntity.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>Gibt <see cref="T:System.Object" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfClosed">
      <MemberSignature Language="C#" Value="protected void ThrowIfClosed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfClosed() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.ThrowIfClosed" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfClosed ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfClosed : unit -&gt; unit" Usage="clientEntity.ThrowIfClosed " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfDisposed">
      <MemberSignature Language="C#" Value="protected void ThrowIfDisposed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfDisposed() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.ThrowIfDisposed" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfDisposed ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfDisposed : unit -&gt; unit" Usage="clientEntity.ThrowIfDisposed " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfDisposedOrImmutable">
      <MemberSignature Language="C#" Value="protected void ThrowIfDisposedOrImmutable ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfDisposedOrImmutable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.ThrowIfDisposedOrImmutable" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfDisposedOrImmutable ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfDisposedOrImmutable : unit -&gt; unit" Usage="clientEntity.ThrowIfDisposedOrImmutable " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfDisposedOrNotOpen">
      <MemberSignature Language="C#" Value="protected void ThrowIfDisposedOrNotOpen ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfDisposedOrNotOpen() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.ThrowIfDisposedOrNotOpen" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfDisposedOrNotOpen ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfDisposedOrNotOpen : unit -&gt; unit" Usage="clientEntity.ThrowIfDisposedOrNotOpen " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfFaulted">
      <MemberSignature Language="C#" Value="protected void ThrowIfFaulted ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfFaulted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ClientEntity.ThrowIfFaulted" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfFaulted ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfFaulted : unit -&gt; unit" Usage="clientEntity.ThrowIfFaulted " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>