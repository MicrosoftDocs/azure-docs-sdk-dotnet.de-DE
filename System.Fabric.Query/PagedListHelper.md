<Type Name="PagedListHelper" FullName="System.Fabric.Query.PagedListHelper">
  <TypeSignature Language="C#" Value="public static class PagedListHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PagedListHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.PagedListHelper" />
  <TypeSignature Language="VB.NET" Value="Public Module PagedListHelper" />
  <TypeSignature Language="F#" Value="type PagedListHelper = class" />
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
      <para>
            Erweiterungen für ausgelagerten listenvorgänge.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToArray&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T[] ToArray&lt;T&gt; (this System.Fabric.Query.PagedList&lt;T&gt; list);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T[] ToArray&lt;T&gt;(class System.Fabric.Query.PagedList`1&lt;!!T&gt; list) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.PagedListHelper.ToArray``1(System.Fabric.Query.PagedList{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToArray(Of T) (list As PagedList(Of T)) As T()" />
      <MemberSignature Language="F#" Value="static member ToArray : System.Fabric.Query.PagedList&lt;'T&gt; -&gt; 'T[]" Usage="System.Fabric.Query.PagedListHelper.ToArray list" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T[]</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="list" Type="System.Fabric.Query.PagedList&lt;T&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="T">
          <para>Der Typ der List-Objekte.</para>
        </typeparam>
        <param name="list">
          <para>Der ausgelagerte Liste.</para>
        </param>
        <summary>
          <para>
            Gibt ein Array mit den Elementen in der ausgelagerten Liste zurück.
            </para>
        </summary>
        <returns>
          <para>Das Array.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>