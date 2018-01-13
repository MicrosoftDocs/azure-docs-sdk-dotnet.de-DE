<Type Name="IStateProviderReplica2" FullName="Microsoft.ServiceFabric.Data.IStateProviderReplica2">
  <TypeSignature Language="C#" Value="public interface IStateProviderReplica2 : Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProviderReplica2 implements class Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProviderReplica2&#xA;Implements IStateProviderReplica" />
  <TypeSignature Language="F#" Value="type IStateProviderReplica2 = interface&#xA;    interface IStateProviderReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Definiert Methoden, die ein Replikat des zuverlässigen Zustand Anbieter, für Service Fabric implementieren muss, damit zu interagieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Funktion wird aufgerufen, nachdem die Wiederherstellung auf dem Replikat durchgeführt wurde.
            </summary>
        <value>
            Funktion wird aufgerufen, wenn der Status des Replikats durch das Framework erfolgreich wiederhergestellt wurde
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>