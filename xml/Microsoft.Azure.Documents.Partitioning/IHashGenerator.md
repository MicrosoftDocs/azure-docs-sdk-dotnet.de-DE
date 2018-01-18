<Type Name="IHashGenerator" FullName="Microsoft.Azure.Documents.Partitioning.IHashGenerator">
  <TypeSignature Language="C#" Value="public interface IHashGenerator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHashGenerator" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHashGenerator" />
  <TypeSignature Language="F#" Value="type IHashGenerator = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for interfaces used with IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="18039-101">Eine Schnittstelle dar, durch die <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> zum Partitionieren von Daten mit konsistenten hashing im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="18039-101">An interface used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> to partition data using consistent hashing in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="18039-102">Unterstützung für Schnittstellen, die mit IPartitionResolver ist mittlerweile veraltet.</span><span class="sxs-lookup"><span data-stu-id="18039-102">Support for interfaces used with IPartitionResolver is now obsolete.</span></span> <span data-ttu-id="18039-103">Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="18039-103">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
    </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  </Docs>
  <Members>
    <Member MemberName="ComputeHash">
      <MemberSignature Language="C#" Value="public byte[] ComputeHash (byte[] key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] ComputeHash(unsigned int8[] key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.IHashGenerator.ComputeHash(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ComputeHash (key As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member ComputeHash : byte[] -&gt; byte[]" Usage="iHashGenerator.ComputeHash key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="18039-104">Ein Schlüssel, dargestellt durch ein Array von bytes</span><span class="sxs-lookup"><span data-stu-id="18039-104">A key represented by an array of bytes</span></span></param>
        <summary>
            <span data-ttu-id="18039-105">Erstellt einen Hashwert für ein Array von Bytes in ein neues Array von Bytes, das den Ausgabehash im Azure-Cosmos-DB-Dienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="18039-105">Hashes an array of bytes into a new array of bytes that represents the output hash in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="18039-106">Ein Array von Bytes, die den Ausgabehash darstellt.</span><span class="sxs-lookup"><span data-stu-id="18039-106">An array of bytes that represents the output hash.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>