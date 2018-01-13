<Type Name="IInheritedBehaviors" FullName="Microsoft.Azure.Batch.IInheritedBehaviors">
  <TypeSignature Language="C#" Value="public interface IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="VB.NET" Value="Public Interface IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type IInheritedBehaviors = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Methoden und Eigenschaften, die aus dem Instanziieren übergeordneten Objekt geerbt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Auflistung wird anfänglich durch Instanziierung oder durch Kopieren aus dem Instanziieren übergeordneten Objekt (Vererbung) aufgefüllt.
            In diesem Modell die Sammlungen sind unabhängig, aber die Elemente sind freigegebene Verweise.
            Mitglieder dieser Sammlung ändern oder Anpassen von Verhaltensweisen von Clientobjekten Azure Batch-Dienst.
            Diese Verhaltensweisen werden in der Regel durch alle Instanzen der untergeordneten Klasse geerbt.  
            Änderungen werden in der Reihenfolge der Auflistung angewendet.
            Der letzte write Wins.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>