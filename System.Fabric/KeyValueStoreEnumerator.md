<Type Name="KeyValueStoreEnumerator" FullName="System.Fabric.KeyValueStoreEnumerator">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreEnumerator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreEnumerator extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreEnumerator" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreEnumerator" />
  <TypeSignature Language="F#" Value="type KeyValueStoreEnumerator = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Liest den Inhalt der lokalen Speicher eines sekundären Replikats, innerhalb des Kontexts eines Rückrufs Abschluss kopieren. </para>
      <seealso cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</para>
        </param>
        <summary>
          <para>Listet den Inhalt der lokalen Speicher und enthält den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für den Inhalt der lokalen Speicher.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</para>
        </param>
        <param name="strictPrefix">
          <para>Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben. Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind. Der Standardwert ist <b>True</b>.</para>
        </param>
        <summary>
          <para>Listet den Inhalt der lokalen Speicher und enthält den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für den Inhalt der lokalen Speicher.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>Gibt eine optionale präfixfilter während der Enumeration anwenden.</para>
        </param>
        <summary>
          <para>Listet den Inhalt der lokalen Speicher, aber schließt den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für den Inhalt der lokalen Speicher.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</para>
        </param>
        <param name="strictPrefix">
          <para>Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben. Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind. Der Standardwert ist <b>True</b>.</para>
        </param>
        <summary>
          <para>Listet den Inhalt der lokalen Speicher, aber schließt den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für den Inhalt der lokalen Speicher.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>