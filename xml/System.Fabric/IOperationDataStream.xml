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
      <para> <span data-ttu-id="f96dd-101">Ein <see cref="T:System.Fabric.IOperationDataStream" /> kapselt einen Stream von <see cref="T:System.Fabric.OperationData" /> Objekte, die zwischen primären und sekundären Replikat ausgetauscht werden.</span><span class="sxs-lookup"><span data-stu-id="f96dd-101">An <see cref="T:System.Fabric.IOperationDataStream" /> encapsulates a stream of <see cref="T:System.Fabric.OperationData" /> objects that are exchanged between Primary replica and Secondary replica.</span></span>
            <span data-ttu-id="f96dd-102">-Objekte implementiert, <see cref="T:System.Fabric.IOperationDataStream" /> während des Kopiervorgangs verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f96dd-102">Objects that implement <see cref="T:System.Fabric.IOperationDataStream" /> are used during the copy process.</span></span>
            <span data-ttu-id="f96dd-103">Beide Kopie Kontext <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> -Methode, die aus dem sekundären Replikat, auf dem primären Replikat und den Kopierstatus gesendet wird <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> Methode implementieren die <see cref="T:System.Fabric.IOperationDataStream" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="f96dd-103">Both the copy context <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method that is sent from the Secondary replica to the Primary replica and the copy state <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> method implement the <see cref="T:System.Fabric.IOperationDataStream" /> interface.</span></span></para>
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
          <para><span data-ttu-id="f96dd-104">Bietet einen Mechanismus zum Abbrechen des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f96dd-104">Provides a mechanism to cancel the asynchronous operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f96dd-105">Ruft den nächsten <see cref="T:System.Fabric.OperationData" /> -Objekt aus der <see cref="T:System.Fabric.IOperationDataStream" />.</span><span class="sxs-lookup"><span data-stu-id="f96dd-105">Gets the next <see cref="T:System.Fabric.OperationData" /> object from the <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f96dd-106">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.Fabric.OperationData" />.</span><span class="sxs-lookup"><span data-stu-id="f96dd-106">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="f96dd-107">Wird Null zurückgegeben zeigt das System, dass die Übertragung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f96dd-107">Returning null indicates to the system that the transfer is complete.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>