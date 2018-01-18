<Type Name="TransactionBase" FullName="System.Fabric.TransactionBase">
  <TypeSignature Language="C#" Value="public abstract class TransactionBase : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TransactionBase extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TransactionBase&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TransactionBase = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="6f9aa-101">Stellt eine abstrakte Basisklasse für eine Transaktion bereit.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-101">Provides an abstract base class for a transaction.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="transactionBase.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-102">Führt anwendungsspezifische Aufgaben, die Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-102">Performs application-defined tasks that are associated with freeing, releasing, or resetting unmanaged resources.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~TransactionBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="transactionBase.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-103">Ermöglicht einem Objekt zu dem Versuch, Ressourcen freizugeben und andere Bereinigungen durchzuführen, bevor es von der Garbagecollection freigegeben wird.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-103">Enables an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Guid Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TransactionBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Guid" />
      <MemberSignature Language="F#" Value="member this.Id : Guid" Usage="System.Fabric.TransactionBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-104">Ruft die ID der Transaktion als eine <see cref="T:System.Guid" />.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-104">Gets the ID of the transaction as a <see cref="T:System.Guid" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6f9aa-105">Die Transaktions-ID als ein <see cref="T:System.Guid" />.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-105">The transaction ID as a <see cref="T:System.Guid" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDisposed">
      <MemberSignature Language="C#" Value="protected bool IsDisposed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsDisposed() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.IsDisposed" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsDisposed () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDisposed : unit -&gt; bool" Usage="transactionBase.IsDisposed " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-106">Ruft einen Wert, der angibt, ob das Objekt verworfen wurde.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-106">Gets a value that indicates whether the object has been disposed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="6f9aa-107">Gibt <languageKeyword>"true"</languageKeyword> , wenn das Objekt freigegeben wurde; andernfalls wird <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-107">Returns <languageKeyword>true</languageKeyword> if the object has been disposed; otherwise, returns <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsolationLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.TransactionIsolationLevel IsolationLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TransactionIsolationLevel IsolationLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TransactionBase.IsolationLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsolationLevel As TransactionIsolationLevel" />
      <MemberSignature Language="F#" Value="member this.IsolationLevel : System.Fabric.TransactionIsolationLevel" Usage="System.Fabric.TransactionBase.IsolationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-108">Ruft die Isolationsstufe der Transaktion als eine <see cref="T:System.Fabric.TransactionIsolationLevel" />.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-108">Gets the isolation level of the transaction as a <see cref="T:System.Fabric.TransactionIsolationLevel" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6f9aa-109">Ein <see cref="T:System.Fabric.TransactionIsolationLevel" /> Objekt, das die Isolationsstufe der Transaktion darstellt.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-109">A <see cref="T:System.Fabric.TransactionIsolationLevel" /> object that represents the isolation level of the transaction.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6f9aa-110">Die Isolationsstufe der Transaktion bestimmt, welche Ebene des Zugriffs auf flüchtige Daten, die andere Transaktionen sein, damit eine Transaktion abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-110">The isolation level of a transaction determines what level of access to volatile data other transactions have before a transaction finishes.</span></span> <span data-ttu-id="6f9aa-111">Weitere Informationen zu Isolationsstufen finden Sie in der Dokumentation für die <see cref="T:System.Fabric.TransactionIsolationLevel" /> Enumeration.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-111">For more information about isolation levels, see the documentation for the <see cref="T:System.Fabric.TransactionIsolationLevel" /> enumeration.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected internal virtual void OnDispose ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance void OnDispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.OnDispose" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Sub OnDispose ()" />
      <MemberSignature Language="F#" Value="abstract member OnDispose : unit -&gt; unit&#xA;override this.OnDispose : unit -&gt; unit" Usage="transactionBase.OnDispose " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6f9aa-112">Das Dispose-Ereignis tritt auf, wenn die Transaktion, der über gelöscht wird die <languageKeyword>OnDispose</languageKeyword> Methode.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-112">The dispose event occurs when the transaction is disposed of through the <languageKeyword>OnDispose</languageKeyword> method.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="6f9aa-113">Zum Überschreiben <see cref="M:System.Fabric.Transaction.OnDispose" />, achten Sie darauf, dass Sie zum Aufrufen der <languageKeyword>OnDispose</languageKeyword> Methode in der Basisklasse.</span><span class="sxs-lookup"><span data-stu-id="6f9aa-113">When overriding <see cref="M:System.Fabric.Transaction.OnDispose" />, be sure to call the <languageKeyword>OnDispose</languageKeyword> method on the base class.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>