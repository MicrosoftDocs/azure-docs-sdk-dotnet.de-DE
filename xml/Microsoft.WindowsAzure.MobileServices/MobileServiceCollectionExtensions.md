<Type Name="MobileServiceCollectionExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceCollectionExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceCollectionExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceCollectionExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceCollectionExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3bccf-101">Stellt Erweiterungsmethoden bereit, auf <see cref="T:IMobileServiceTableQuery`1{T}" /> und <see cref="T:IMobileServiceTable`1{T}" /> um sie in einer Auflistung einzufügen.</span><span class="sxs-lookup"><span data-stu-id="3bccf-101">Provides extension methods on <see cref="T:IMobileServiceTableQuery`1{T}" /> and <see cref="T:IMobileServiceTable`1{T}" /> to wrap them in a collection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToCollectionAsync&lt;TTable&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt; (this Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;TTable&gt; table, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2&lt;!!TTable, !!TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!!TTable&gt; table, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTable{``0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToCollectionAsync(Of TTable) (table As IMobileServiceTable(Of TTable), Optional pageSize As Integer = 0) As Task(Of MobileServiceCollection(Of TTable, TTable))" />
      <MemberSignature Language="F#" Value="static member ToCollectionAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'able&gt; * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'able&gt;&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync (table, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TTable" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;TTable&gt;" RefType="this" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <typeparam name="TTable">To be added.</typeparam>
        <param name="table">
            <span data-ttu-id="3bccf-102">Die Tabelle, aus der die neue Sammlung erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3bccf-102">The table from which to create the new collection.</span></span> 
            </param>
        <param name="pageSize">
            <span data-ttu-id="3bccf-103">Optionale Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="3bccf-103">Optional page size.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3bccf-104">Erstellen einer neuen Auflistung basierend auf der Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="3bccf-104">Create a new collection based on the table.</span></span>
            </summary>
        <returns><span data-ttu-id="3bccf-105">Die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="3bccf-105">The collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToCollectionAsync&lt;TTable&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt; (this Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2&lt;!!TTable, !!TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!TTable&gt; query, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToCollectionAsync(Of TTable) (query As IMobileServiceTableQuery(Of TTable), Optional pageSize As Integer = 0) As Task(Of MobileServiceCollection(Of TTable, TTable))" />
      <MemberSignature Language="F#" Value="static member ToCollectionAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'able&gt;&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync (query, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions/&lt;ToCollectionAsync&gt;d__0`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TTable" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" RefType="this" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <typeparam name="TTable">To be added.</typeparam>
        <param name="query">
            <span data-ttu-id="3bccf-106">Die Abfrage, um Daten auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="3bccf-106">The query to evaluate for data.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="3bccf-107">Optionale Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="3bccf-107">Optional page size.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3bccf-108">Erstellen einer neuen Auflistung basierend auf der Abfrage an.</span><span class="sxs-lookup"><span data-stu-id="3bccf-108">Create a new collection based on the query.</span></span>
            </summary>
        <returns><span data-ttu-id="3bccf-109">Die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="3bccf-109">The collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToCollectionAsync&lt;TTable&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;TTable&gt; table, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2&lt;!!TTable, !!TTable&gt;&gt; ToCollectionAsync&lt;TTable&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!TTable&gt; table, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync``1(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToCollectionAsync(Of TTable) (table As IMobileServiceSyncTable(Of TTable), Optional pageSize As Integer = 0) As Task(Of MobileServiceCollection(Of TTable, TTable))" />
      <MemberSignature Language="F#" Value="static member ToCollectionAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'able&gt; * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'able&gt;&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollectionExtensions.ToCollectionAsync (table, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TTable" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;TTable&gt;" RefType="this" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <typeparam name="TTable">To be added.</typeparam>
        <param name="table">
            <span data-ttu-id="3bccf-110">Die lokale Tabelle aus der die neue Sammlung erstellt.</span><span class="sxs-lookup"><span data-stu-id="3bccf-110">The local table from which to create the new collection.</span></span> 
            </param>
        <param name="pageSize">
            <span data-ttu-id="3bccf-111">Optionale Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="3bccf-111">Optional page size.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3bccf-112">Erstellen einer neuen Auflistung basierend auf der lokalen Tabelle an.</span><span class="sxs-lookup"><span data-stu-id="3bccf-112">Create a new collection based on the local table.</span></span>
            </summary>
        <returns><span data-ttu-id="3bccf-113">Die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="3bccf-113">The collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>