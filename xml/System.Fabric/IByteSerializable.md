<Type Name="IByteSerializable" FullName="System.Fabric.IByteSerializable">
  <TypeSignature Language="C#" Value="public interface IByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IByteSerializable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IByteSerializable" />
  <TypeSignature Language="F#" Value="type IByteSerializable = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="4ed19-101">Macht die Methoden, um das Objekt in ein Byte [] Serialisieren oder Deserialisieren des Objekts aus einem Byte]</span><span class="sxs-lookup"><span data-stu-id="4ed19-101">Exposes the methods to serialize the object into a byte[] or deserialize the object from a byte[]</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromBytes">
      <MemberSignature Language="C#" Value="public void FromBytes (byte[] data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FromBytes(unsigned int8[] data) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IByteSerializable.FromBytes(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub FromBytes (data As Byte())" />
      <MemberSignature Language="F#" Value="abstract member FromBytes : byte[] -&gt; unit" Usage="iByteSerializable.FromBytes data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="4ed19-102">Byte []-Darstellung des Objekts</span><span class="sxs-lookup"><span data-stu-id="4ed19-102">byte[] representation of the object</span></span></param>
        <summary>
            <span data-ttu-id="4ed19-103">Füllt ein Objekt aus einem Byte]</span><span class="sxs-lookup"><span data-stu-id="4ed19-103">Populates an object from a byte[]</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToBytes">
      <MemberSignature Language="C#" Value="public byte[] ToBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] ToBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IByteSerializable.ToBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBytes () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member ToBytes : unit -&gt; byte[]" Usage="iByteSerializable.ToBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4ed19-104">Ruft ein Byte []-Darstellung des Objekts ab</span><span class="sxs-lookup"><span data-stu-id="4ed19-104">Retrieves a byte[] representation of the object</span></span>
            </summary>
        <returns><span data-ttu-id="4ed19-105">Ein Byte]</span><span class="sxs-lookup"><span data-stu-id="4ed19-105">A byte[]</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>