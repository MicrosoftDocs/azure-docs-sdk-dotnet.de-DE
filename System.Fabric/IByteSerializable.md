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
      <para>Macht die Methoden, um das Objekt in ein Byte [] Serialisieren oder Deserialisieren des Objekts aus einem Byte]</para>
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
        <param name="data">Byte []-Darstellung des Objekts</param>
        <summary>
            Füllt ein Objekt aus einem Byte]
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
            Ruft ein Byte []-Darstellung des Objekts ab
            </summary>
        <returns>Ein Byte]</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>