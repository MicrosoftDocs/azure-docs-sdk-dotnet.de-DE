<Type Name="IOperationDataStream" FullName="System.Fabric.IOperationDataStream">
  <TypeSignature Language="C#" Value="public interface IOperationDataStream" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationDataStream" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperationDataStream" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationDataStream" />
  <TypeSignature Language="F#" Value="type IOperationDataStream = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para> Ein <see cref="T:System.Fabric.IOperationDataStream" /> kapselt einen Stream von <see cref="T:System.Fabric.OperationData" /> Objekte, die zwischen primären und sekundären Replikat ausgetauscht werden.
            -Objekte implementiert, <see cref="T:System.Fabric.IOperationDataStream" /> während des Kopiervorgangs verwendet werden.
            Beide Kopie Kontext <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> -Methode, die aus dem sekundären Replikat, auf dem primären Replikat und den Kopierstatus gesendet wird <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> Methode implementieren die <see cref="T:System.Fabric.IOperationDataStream" /> Schnittstelle.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt; GetNextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.OperationData&gt; GetNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;" Usage="iOperationDataStream.GetNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Bietet einen Mechanismus zum Abbrechen des asynchronen Vorgangs.</para>
        </param>
        <summary>
          <para>Ruft den nächsten <see cref="T:System.Fabric.OperationData" /> -Objekt aus der <see cref="T:System.Fabric.IOperationDataStream" />.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.Fabric.OperationData" />.</para>
        </returns>
        <remarks>
          <para>
                Wird Null zurückgegeben zeigt das System, dass die Übertragung abgeschlossen ist.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>