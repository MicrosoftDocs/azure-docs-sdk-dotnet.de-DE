<Type Name="FabricRuntime" FullName="System.Fabric.FabricRuntime">
  <TypeSignature Language="C#" Value="public sealed class FabricRuntime : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FabricRuntime extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricRuntime" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricRuntime&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricRuntime = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Können benutzerdefinierte Hosts erhalten ihre <see cref="T:System.Fabric.CodePackageActivationContext" />, auch auf den erforderlichen Dienst Factorys registrieren [ <see cref="T:System.Fabric.IStatelessServiceFactory" />, <see cref="T:System.Fabric.IStatefulServiceFactory" />, oder <see cref="T:System.Fabric.ServiceGroupFactory" />] oder direkt Diensttypen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt.</para>
        </summary>
        <returns>
          <para>Ein neu erstelltes <see cref="T:System.Fabric.FabricRuntime" /> Objekt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create (Action fabricExitCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create(class System.Action fabricExitCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create(System.Action)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (fabricExitCallback As Action) As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : Action -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create fabricExitCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para>Die Aktion, die ausgeführt werden, wenn die Laufzeit beendet wird oder beendet wird.</para>
        </param>
        <summary>
          <para>Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt mit einer festgelegten Rückruffunktion, die ausgeführt wird, wenn die zugrunde liegenden Laufzeit beendet wird oder aus irgendeinem Grund beendet wird.</para>
        </summary>
        <returns>
          <para>Ein neu erstelltes <see cref="T:System.Fabric.FabricRuntime" />Objekt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> asynchron mit dem angegebenen Objekt <paramref name="timeout" /> und <paramref name="cancellationToken" />.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (Action fabricExitCallback, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(class System.Action fabricExitCallback, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.Action,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Action * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (fabricExitCallback, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para>Die Aktion, die ausgeführt werden, wenn die Laufzeit beendet wird oder beendet wird.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt asynchron mit der angegebenen Rückruf-Funktion, die ausgeführt wird, wenn die zugrunde liegenden Laufzeit beendet wird oder aus irgendeinem Grund beendet <paramref name="timeout" />, und <paramref name="cancellationToken" />. </para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricRuntime.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Verwirft die <see cref="T:System.Fabric.FabricRuntime" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.CodePackageActivationContext GetActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.CodePackageActivationContext GetActivationContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActivationContext () As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="static member GetActivationContext : unit -&gt; System.Fabric.CodePackageActivationContext" Usage="System.Fabric.FabricRuntime.GetActivationContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft ab den aktuellen <see cref="T:System.Fabric.FabricRuntime" />des <see cref="T:System.Fabric.CodePackageActivationContext" />.</para>
        </summary>
        <returns>
          <para>Der Aktivierungskontext.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetActivationContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;" Usage="System.Fabric.FabricRuntime.GetActivationContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die maximale Zeitdauer wird Service Fabric, diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException zulassen</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft ab den aktuellen <see cref="T:System.Fabric.FabricRuntime" />des <see cref="T:System.Fabric.CodePackageActivationContext" /> asynchron mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.NodeContext GetNodeContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.NodeContext GetNodeContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNodeContext () As NodeContext" />
      <MemberSignature Language="F#" Value="static member GetNodeContext : unit -&gt; System.Fabric.NodeContext" Usage="System.Fabric.FabricRuntime.GetNodeContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die Knoten Context-Objekt, das Informationen zu Fabric-Knoten enthält. </para>
        </summary>
        <returns>
          <para>Der Knotenkontext.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt; GetNodeContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeContext&gt; GetNodeContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNodeContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;" Usage="System.Fabric.FabricRuntime.GetNodeContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die maximale Zeitdauer wird Service Fabric, diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException zulassen</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft Knotenkontext von Fabric-Knoten asynchron mit Timeout und ein Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactory">
      <MemberSignature Language="C#" Value="public void RegisterServiceGroupFactory (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceGroupFactory(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactory(System.String,System.Fabric.ServiceGroupFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceGroupFactory (serviceGroupTypeName As String, factory As ServiceGroupFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactory : string * System.Fabric.ServiceGroupFactory -&gt; unit" Usage="fabricRuntime.RegisterServiceGroupFactory (serviceGroupTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para>Der Typname des Diensttyps Dienstgruppe (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateServiceGroup übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.ServiceGroupFactory" /> können die den angegebenen Diensttyp Gruppe erstellen.</para>
        </param>
        <summary>
          <para>Registriert das angegebene <see cref="T:System.Fabric.ServiceGroupFactory" /> für den angegebenen Typ.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactoryAsync(System.String,System.Fabric.ServiceGroupFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactoryAsync : string * System.Fabric.ServiceGroupFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceGroupFactoryAsync (serviceGroupTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para>Der Typname des Diensttyps Dienstgruppe (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateServiceGroup übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.ServiceGroupFactory" /> können die den angegebenen Diensttyp Gruppe erstellen.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Asynchron registriert das angegebene <see cref="T:System.Fabric.ServiceGroupFactory" /> für den angegebenen Diensttyp des Gruppe mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceType">
      <MemberSignature Language="C#" Value="public void RegisterServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceType : string * Type -&gt; unit" Usage="fabricRuntime.RegisterServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="serviceTypeImplementation">
          <para>Der qualifizierte Dienst Typ, der dem angegebenen implementiert <paramref name="serviceTypeName" />.</para>
        </param>
        <summary>
          <para>Ordnet die angegebene <paramref name="serviceTypeName" /> mit der tatsächlichen verwalteten Typ, die ihn implementiert. </para>
        </summary>
        <remarks>
          <para>Beachten Sie, dass dieser Mechanismus für die Registrierung der Service-Typ nicht über eine benutzerdefinierte erfordert <see cref="T:System.Fabric.IStatelessServiceFactory" /> oder <see cref="T:System.Fabric.IStatefulServiceFactory" /> zum Zeitpunkt der Registrierung bereitgestellt werden.  Service Fabric eine zur Laufzeit generiert und automatisch zu verwenden.  Wenn für eine benutzerdefinierte Implementierung der Factory erforderlich ist, können Sie implementieren <see cref="T:System.Fabric.IStatelessServiceFactory" /> oder <see cref="T:System.Fabric.IStatefulServiceFactory" /> , und geben Sie diese über die entsprechenden Factory Registrierungsmethoden (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" /> oder <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceTypeAsync (string serviceTypeName, Type serviceTypeImplementation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceTypeAsync(string serviceTypeName, class System.Type serviceTypeImplementation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceTypeAsync(System.String,System.Type,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceTypeAsync : string * Type * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceTypeAsync (serviceTypeName, serviceTypeImplementation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="serviceTypeImplementation">
          <para>Der qualifizierte Dienst Typ, der dem angegebenen implementiert <paramref name="serviceTypeName" />.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ordnet asynchron mit dem tatsächlichen verwalteten Typ die, mit der angegebenen Implementierung, der angegebenen ServiceTypeName <paramref name="timeout" /> und<paramref name="cancellationToken" /></para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.IStatefulServiceFactory" /> können die den angegebenen Typ erstellt.</para>
        </param>
        <summary>
          <para>Registriert das angegebene <see cref="T:System.Fabric.IStatefulServiceFactory" /> für den angegebenen Diensttyp.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactoryAsync : string * System.Fabric.IStatefulServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatefulServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.IStatefulServiceFactory" /> können die den angegebenen Typ erstellt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Registriert das angegebene <see cref="T:System.Fabric.IStatefulServiceFactory" /> für den angegebenen Typ mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</para>
        </summary>
        <returns>
          <para>Die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.IStatelessServiceFactory" /> können die den angegebenen Typ erstellt.</para>
        </param>
        <summary>
          <para>Registriert das angegebene <see cref="T:System.Fabric.IStatelessServiceFactory" /> für den angegebenen Diensttyp.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactoryAsync : string * System.Fabric.IStatelessServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatelessServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>Der Typname des Diensttyps (als Zeichenfolge).  Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</para>
        </param>
        <param name="factory">
          <para>Die <see cref="T:System.Fabric.IStatelessServiceFactory" /> können die den angegebenen Typ erstellt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Asynchron registriert das angegebene <see cref="T:System.Fabric.IStatelessServiceFactory" /> für den angegebenen Diensttyp, mit dem angegebenen <paramref name="timeout" /> und<paramref name="cancellationToken" /></para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>