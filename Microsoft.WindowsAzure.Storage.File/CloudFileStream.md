<Type Name="CloudFileStream" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileStream">
  <TypeSignature Language="C#" Value="public abstract class CloudFileStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CloudFileStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CloudFileStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type CloudFileStream = class&#xA;    inherit Stream" />
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
            Stellt einen Datenstrom zum Schreiben in eine Datei dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CloudFileStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.#ctor" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.BeginCommit(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginCommit (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCommit : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileStream.BeginCommit (callback, state)" />
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
        <param name="callback">Ein optionaler asynchroner Rückruf, der aufgerufen werden, wenn das Commit abgeschlossen ist.</param>
        <param name="state">Ein vom Benutzer bereitgestelltes Objekt, das dieser bestimmten asynchronen commitanforderung von anderen Anforderungen unterscheidet.</param>
        <summary>
            Startet einen asynchronen Commitvorgang.
            </summary>
        <returns>Ein <c>ICancellableAsyncResult</c> , die den asynchronen Commit, der möglicherweise noch aussteht darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFlush">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.BeginFlush(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginFlush (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFlush : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileStream.BeginFlush (callback, state)" />
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
        <param name="callback">Ein optionaler asynchroner Rückruf, der nach Abschluss des Löschvorgangs aufgerufen wird.</param>
        <param name="state">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Löschanforderung von anderen Anforderungen unterscheidet.</param>
        <summary>
            Beginnt eine asynchrone Leerung ab.
            </summary>
        <returns>Ein <c>ICancellableAsyncResult</c> , die den asynchronen Löschvorgangs, der möglicherweise noch aussteht darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public abstract void Commit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Commit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.Commit" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Commit ()" />
      <MemberSignature Language="F#" Value="abstract member Commit : unit -&gt; unit" Usage="cloudFileStream.Commit " />
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
            Löscht sämtliche Puffer für diesen Datenstrom, verursacht die Ausgabe aller gepufferten Daten in die zugrunde liegende Datei geschrieben werden sollen, und führt einen Commit für die Datei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCommit">
      <MemberSignature Language="C#" Value="public abstract void EndCommit (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCommit(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.EndCommit(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndCommit (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCommit : IAsyncResult -&gt; unit" Usage="cloudFileStream.EndCommit asyncResult" />
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
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Wartet, bis der ausstehende asynchrone Commit abgeschlossen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFlush">
      <MemberSignature Language="C#" Value="public abstract void EndFlush (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFlush(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.EndFlush(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndFlush (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFlush : IAsyncResult -&gt; unit" Usage="cloudFileStream.EndFlush asyncResult" />
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
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Wartet, bis der ausstehende asynchrone Leerung abgeschlossen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>