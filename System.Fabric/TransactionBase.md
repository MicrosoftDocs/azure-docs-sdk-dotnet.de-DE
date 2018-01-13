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
      <para>Stellt eine abstrakte Basisklasse für eine Transaktion bereit.</para>
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
          <para>Führt anwendungsspezifische Aufgaben, die Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zugeordnet sind.</para>
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
          <para>Ermöglicht einem Objekt zu dem Versuch, Ressourcen freizugeben und andere Bereinigungen durchzuführen, bevor es von der Garbagecollection freigegeben wird.</para>
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
          <para>Ruft die ID der Transaktion als eine <see cref="T:System.Guid" />.</para>
        </summary>
        <value>
          <para>Die Transaktions-ID als ein <see cref="T:System.Guid" />.</para>
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
          <para>Ruft einen Wert, der angibt, ob das Objekt verworfen wurde.</para>
        </summary>
        <returns>
          <para>Gibt <languageKeyword>"true"</languageKeyword> , wenn das Objekt freigegeben wurde; andernfalls wird <languageKeyword>"false"</languageKeyword>.</para>
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
          <para>Ruft die Isolationsstufe der Transaktion als eine <see cref="T:System.Fabric.TransactionIsolationLevel" />.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.TransactionIsolationLevel" /> Objekt, das die Isolationsstufe der Transaktion darstellt.</para>
        </value>
        <remarks>
          <para>Die Isolationsstufe der Transaktion bestimmt, welche Ebene des Zugriffs auf flüchtige Daten, die andere Transaktionen sein, damit eine Transaktion abgeschlossen ist. Weitere Informationen zu Isolationsstufen finden Sie in der Dokumentation für die <see cref="T:System.Fabric.TransactionIsolationLevel" /> Enumeration.</para>
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
          <para>Das Dispose-Ereignis tritt auf, wenn die Transaktion, der über gelöscht wird die <languageKeyword>OnDispose</languageKeyword> Methode.</para>
        </summary>
        <remarks>
          <para>Zum Überschreiben <see cref="M:System.Fabric.Transaction.OnDispose" />, achten Sie darauf, dass Sie zum Aufrufen der <languageKeyword>OnDispose</languageKeyword> Methode in der Basisklasse.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>