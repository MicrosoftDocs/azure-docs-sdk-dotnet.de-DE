<Type Name="StringExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.StringExtensions">
  <TypeSignature Language="C#" Value="public static class StringExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StringExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.StringExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Class StringExtensions" />
  <TypeSignature Language="F#" Value="type StringExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FindNewline">
      <MemberSignature Language="C#" Value="public static int FindNewline (byte[] buffer, int startOffset, int length, bool reverse, System.Text.Encoding encoding, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 FindNewline(unsigned int8[] buffer, int32 startOffset, int32 length, bool reverse, class System.Text.Encoding encoding, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.StringExtensions.FindNewline(System.Byte[],System.Int32,System.Int32,System.Boolean,System.Text.Encoding,System.String)" />
      <MemberSignature Language="F#" Value="static member FindNewline : byte[] * int * int * bool * System.Text.Encoding * string -&gt; int" Usage="Microsoft.Azure.Management.DataLake.Store.StringExtensions.FindNewline (buffer, startOffset, length, reverse, encoding, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="startOffset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="reverse" Type="System.Boolean" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="buffer">Der Puffer in gesucht werden soll.</param>
        <param name="startOffset">Der Index des ersten Bytes auf dem mit der Suche an.</param>
        <param name="length">Die Anzahl der Bytes, die zu suchen, beginnend mit dem angegebenen StartOffset.</param>
        <param name="reverse">Bei "true", sucht von der StartOffset zu Beginn des Puffers. Wenn "false" sucht nach oben.</param>
        <param name="encoding">To be added.</param>
        <param name="delimiter">To be added.</param>
        <summary>
            Der Index gesucht in den angegebenen Puffer ein neue Zeilenumbruchzeichen entweder das erste oder das letzte (basierend auf den Parametern).
            Wenn ein kombinierten Zeilenumbruch (\r\n), ist der zurückgegebene Index des letzten Zeichens in der Sequenz.
            </summary>
        <returns>Der Index des nächsten Zeilenumbruchzeichen in der Sequenz (auf der Grundlage der Richtung), die gefunden wurde. Gibt-1 zurück, falls keine gefunden. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>