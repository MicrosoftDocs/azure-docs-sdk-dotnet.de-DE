<Type Name="IReplicator" FullName="System.Fabric.IReplicator">
  <TypeSignature Language="C#" Value="public interface IReplicator : System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicator implements class System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicator&#xA;Implements IPrimaryReplicator" />
  <TypeSignature Language="F#" Value="type IReplicator = interface&#xA;    interface IPrimaryReplicator" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IPrimaryReplicator</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iReplicator.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeRoleAsync (System.Fabric.Epoch epoch, System.Fabric.ReplicaRole role, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ChangeRoleAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Fabric.ReplicaRole role, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.Epoch * System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.ChangeRoleAsync (epoch, role, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="role">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCatchUpCapability">
      <MemberSignature Language="C#" Value="public long GetCatchUpCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCatchUpCapability() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCatchUpCapability" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCatchUpCapability () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCatchUpCapability : unit -&gt; int64" Usage="iReplicator.GetCatchUpCapability " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Nur zur internen Verwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentProgress">
      <MemberSignature Language="C#" Value="public long GetCurrentProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCurrentProgress() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentProgress () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCurrentProgress : unit -&gt; int64" Usage="iReplicator.GetCurrentProgress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iReplicator.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.UpdateEpochAsync (epoch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
        <returns>
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>