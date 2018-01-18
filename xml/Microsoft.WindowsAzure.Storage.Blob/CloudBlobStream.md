<Type Name="CloudBlobStream" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream">
  <TypeSignature Language="C#" Value="public abstract class CloudBlobStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CloudBlobStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CloudBlobStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type CloudBlobStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8785b-101">Stellt einen Datenstrom zum Schreiben in ein Blob dar.</span><span class="sxs-lookup"><span data-stu-id="8785b-101">Represents a stream for writing to a blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CloudBlobStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCommit">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCommit (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCommit(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.BeginCommit(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginCommit (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCommit : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobStream.BeginCommit (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="8785b-102">Ein optionaler asynchroner Rückruf, der aufgerufen werden, wenn das Commit abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="8785b-102">An optional asynchronous callback, to be called when the commit is complete.</span></span></param>
        <param name="state"><span data-ttu-id="8785b-103">Ein vom Benutzer bereitgestelltes Objekt, das dieser bestimmten asynchronen commitanforderung von anderen Anforderungen unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="8785b-103">A user-provided object that distinguishes this particular asynchronous commit request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="8785b-104">Startet einen asynchronen Commitvorgang.</span><span class="sxs-lookup"><span data-stu-id="8785b-104">Begins an asynchronous commit operation.</span></span>
            </summary>
        <returns><span data-ttu-id="8785b-105">Ein <c>ICancellableAsyncResult</c> , die den asynchronen Commit, der möglicherweise noch aussteht darstellt.</span><span class="sxs-lookup"><span data-stu-id="8785b-105">An <c>ICancellableAsyncResult</c> that represents the asynchronous commit, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFlush">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.BeginFlush(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginFlush (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFlush : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobStream.BeginFlush (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="8785b-106">Ein optionaler asynchroner Rückruf, der nach Abschluss des Löschvorgangs aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="8785b-106">An optional asynchronous callback, to be called when the flush is complete.</span></span></param>
        <param name="state"><span data-ttu-id="8785b-107">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Löschanforderung von anderen Anforderungen unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="8785b-107">A user-provided object that distinguishes this particular asynchronous flush request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="8785b-108">Beginnt eine asynchrone Leerung ab.</span><span class="sxs-lookup"><span data-stu-id="8785b-108">Begins an asynchronous flush operation.</span></span>
            </summary>
        <returns><span data-ttu-id="8785b-109">Ein <c>ICancellableAsyncResult</c> , die den asynchronen Löschvorgangs, der möglicherweise noch aussteht darstellt.</span><span class="sxs-lookup"><span data-stu-id="8785b-109">An <c>ICancellableAsyncResult</c> that represents the asynchronous flush, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public abstract void Commit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Commit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.Commit" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Commit ()" />
      <MemberSignature Language="F#" Value="abstract member Commit : unit -&gt; unit" Usage="cloudBlobStream.Commit " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8785b-110">Löscht sämtliche Puffer für diesen Datenstrom, verursacht die Ausgabe aller gepufferten Daten in der zugrunde liegenden Blob geschrieben werden sollen, und führt einen Commit für das Blob.</span><span class="sxs-lookup"><span data-stu-id="8785b-110">Clears all buffers for this stream, causes any buffered data to be written to the underlying blob, and commits the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCommit">
      <MemberSignature Language="C#" Value="public abstract void EndCommit (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCommit(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.EndCommit(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndCommit (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCommit : IAsyncResult -&gt; unit" Usage="cloudBlobStream.EndCommit asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="8785b-111">Ein <see cref="T:System.IAsyncResult" /> Objekt mit einem Verweis auf die ausstehende asynchrone Anforderung, um den Vorgang abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="8785b-111">An <see cref="T:System.IAsyncResult" /> object containing a reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="8785b-112">Wartet, bis der ausstehende asynchrone Commit abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="8785b-112">Waits for the pending asynchronous commit to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFlush">
      <MemberSignature Language="C#" Value="public abstract void EndFlush (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFlush(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.EndFlush(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndFlush (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFlush : IAsyncResult -&gt; unit" Usage="cloudBlobStream.EndFlush asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="8785b-113">Ein <see cref="T:System.IAsyncResult" /> Objekt mit einem Verweis auf die ausstehende asynchrone Anforderung, um den Vorgang abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="8785b-113">An <see cref="T:System.IAsyncResult" /> object containing a reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="8785b-114">Wartet, bis der ausstehende asynchrone Leerung abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="8785b-114">Waits for the pending asynchronous flush to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>