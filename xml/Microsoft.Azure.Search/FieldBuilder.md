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
            <span data-ttu-id="0fcc4-101">Erstellt die Felddefinitionen für einen Azure Search-Index durch Reflektieren über einen benutzerdefinierten Modelltyp.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-101">Builds field definitions for an Azure Search index by reflecting over a user-defined model type.</span></span>
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
            <span data-ttu-id="0fcc4-102">Der Typ für den Felder erstellt werden, auf Grundlage ihrer Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-102">The type for which fields will be created, based on its properties.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="0fcc4-103">Erstellt eine Auflistung von <see cref="T:Microsoft.Azure.Search.Models.Field" /> Objekte, die Eigenschaften des angegebenen Typs entspricht.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-103">Creates a collection of <see cref="T:Microsoft.Azure.Search.Models.Field" /> objects corresponding to the properties of the type supplied.</span></span>
            </summary>
        <returns><span data-ttu-id="0fcc4-104">Eine Auflistung von Feldern.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-104">A collection of fields.</span></span></returns>
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
            <span data-ttu-id="0fcc4-105">Der Typ für den Felder erstellt werden, auf Grundlage ihrer Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-105">The type for which fields will be created, based on its properties.</span></span>
            </typeparam>
        <param name="contractResolver">
            <span data-ttu-id="0fcc4-106">Vertrag Konfliktlöser, der <see cref="T:Microsoft.Azure.Search.SearchIndexClient" /> verwenden.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-106">Contract resolver that the <see cref="T:Microsoft.Azure.Search.SearchIndexClient" /> will use.</span></span>
            <span data-ttu-id="0fcc4-107">Dadurch wird sichergestellt, dass die Feldnamen auf eine Weise generiert werden, die konsistent mit der Funktionsweise des Modells serialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-107">This ensures that the field names are generated in a way that is consistent with the way the model will be serialized.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0fcc4-108">Erstellt eine Auflistung von <see cref="T:Microsoft.Azure.Search.Models.Field" /> Objekte, die Eigenschaften des angegebenen Typs entspricht.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-108">Creates a collection of <see cref="T:Microsoft.Azure.Search.Models.Field" /> objects corresponding to the properties of the type supplied.</span></span>
            </summary>
        <returns><span data-ttu-id="0fcc4-109">Eine Auflistung von Feldern.</span><span class="sxs-lookup"><span data-stu-id="0fcc4-109">A collection of fields.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>