<Type Name="SqlFuncs" FullName="Microsoft.Azure.Mobile.Server.SqlFuncs">
  <TypeSignature Language="C#" Value="public static class SqlFuncs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SqlFuncs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.SqlFuncs" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFuncs" />
  <TypeSignature Language="F#" Value="type SqlFuncs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", Justification="Temporary", MessageId="Funcs")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StringConvert">
      <MemberSignature Language="C#" Value="public static string StringConvert (Nullable&lt;double&gt; number);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string StringConvert(valuetype System.Nullable`1&lt;float64&gt; number) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert(System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StringConvert (number As Nullable(Of Double)) As String" />
      <MemberSignature Language="F#" Value="static member StringConvert : Nullable&lt;double&gt; -&gt; string" Usage="Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert number" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Data.Entity.DbFunction("SqlServer", "STR")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="number" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="number">Ein numerischer Ausdruck.</param>
        <summary>Gibt Zeichendaten aus numerischen Daten konvertiert werden.</summary>
        <returns>Der eingegebene Ausdruck in eine Zeichenfolge konvertiert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StringConvert">
      <MemberSignature Language="C#" Value="public static string StringConvert (Nullable&lt;double&gt; number, Nullable&lt;int&gt; length);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string StringConvert(valuetype System.Nullable`1&lt;float64&gt; number, valuetype System.Nullable`1&lt;int32&gt; length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert(System.Nullable{System.Double},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StringConvert (number As Nullable(Of Double), length As Nullable(Of Integer)) As String" />
      <MemberSignature Language="F#" Value="static member StringConvert : Nullable&lt;double&gt; * Nullable&lt;int&gt; -&gt; string" Usage="Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert (number, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Data.Entity.DbFunction("SqlServer", "STR")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="number" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="number">Ein numerischer Ausdruck.</param>
        <param name="length">Die Gesamtlänge der Zeichenfolge. Dazu gehören Dezimaltrennzeichen, Vorzeichen, Ziffern und Leerzeichen. Der Standard ist 10.</param>
        <summary>Gibt Zeichendaten aus numerischen Daten konvertiert werden.</summary>
        <returns>Der numerische Eingabeausdruck in eine Zeichenfolge konvertiert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>