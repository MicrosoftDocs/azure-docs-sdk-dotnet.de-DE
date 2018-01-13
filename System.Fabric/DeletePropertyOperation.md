<Type Name="DeletePropertyOperation" FullName="System.Fabric.DeletePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class DeletePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DeletePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type DeletePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine <see cref="T:System.Fabric.PropertyBatchOperation" /> löscht, die eine angegebene Eigenschaft, falls vorhanden.</para>
    </summary>
    <remarks>
      <para>Beachten Sie, dass, wenn ein <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt ein Fehler auftritt, wird der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletePropertyOperation (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.DeletePropertyOperation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.DeletePropertyOperation : string -&gt; System.Fabric.DeletePropertyOperation" Usage="new System.Fabric.DeletePropertyOperation propertyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft gelöscht werden soll.</para>
        </param>
        <summary>
          <para>Erstellt und instanziiert einen <see cref="T:System.Fabric.DeletePropertyOperation" /> Objekt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>