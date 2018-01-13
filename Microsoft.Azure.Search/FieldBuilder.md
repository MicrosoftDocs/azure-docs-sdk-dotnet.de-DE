<Type Name="FieldBuilder" FullName="Microsoft.Azure.Search.FieldBuilder">
  <TypeSignature Language="C#" Value="public static class FieldBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FieldBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.FieldBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class FieldBuilder" />
  <TypeSignature Language="F#" Value="type FieldBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erstellt die Felddefinitionen für einen Azure Search-Index durch Reflektieren über einen benutzerdefinierten Modelltyp.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildForType&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.FieldBuilder.BuildForType``1" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function BuildForType(Of T) () As IList(Of Field)" />
      <MemberSignature Language="F#" Value="static member BuildForType : unit -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;" Usage="Microsoft.Azure.Search.FieldBuilder.BuildForType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            Der Typ für den Felder erstellt werden, auf Grundlage ihrer Eigenschaften.
            </typeparam>
        <summary>
            Erstellt eine Auflistung von <see cref="T:Microsoft.Azure.Search.Models.Field" /> Objekte, die Eigenschaften des angegebenen Typs entspricht.
            </summary>
        <returns>Eine Auflistung von Feldern.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildForType&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt; (Newtonsoft.Json.Serialization.IContractResolver contractResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt;(class Newtonsoft.Json.Serialization.IContractResolver contractResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.FieldBuilder.BuildForType``1(Newtonsoft.Json.Serialization.IContractResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function BuildForType(Of T) (contractResolver As IContractResolver) As IList(Of Field)" />
      <MemberSignature Language="F#" Value="static member BuildForType : Newtonsoft.Json.Serialization.IContractResolver -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;" Usage="Microsoft.Azure.Search.FieldBuilder.BuildForType contractResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="contractResolver" Type="Newtonsoft.Json.Serialization.IContractResolver" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Der Typ für den Felder erstellt werden, auf Grundlage ihrer Eigenschaften.
            </typeparam>
        <param name="contractResolver">
            Vertrag Konfliktlöser, der <see cref="T:Microsoft.Azure.Search.SearchIndexClient" /> verwenden.
            Dadurch wird sichergestellt, dass die Feldnamen auf eine Weise generiert werden, die konsistent mit der Funktionsweise des Modells serialisiert wird.
            </param>
        <summary>
            Erstellt eine Auflistung von <see cref="T:Microsoft.Azure.Search.Models.Field" /> Objekte, die Eigenschaften des angegebenen Typs entspricht.
            </summary>
        <returns>Eine Auflistung von Feldern.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>