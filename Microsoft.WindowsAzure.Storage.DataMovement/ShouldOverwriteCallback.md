<Type Name="ShouldOverwriteCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback">
  <TypeSignature Language="C#" Value="public delegate bool ShouldOverwriteCallback(object source, object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShouldOverwriteCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ShouldOverwriteCallback(source As Object, destination As Object) As Boolean " />
  <TypeSignature Language="F#" Value="type ShouldOverwriteCallback = delegate of obj * obj -&gt; bool" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Object" />
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Boolean</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source">Die Instanz der Datenquelle verwendet, um das Ziel zu überschreiben.</param>
    <param name="destination">Die Instanz des Ziels, das überschrieben werden.</param>
    <summary>
            Der Rückruf aufgerufen wird, um feststellen, ob ein vorhandenes Ziel überschrieben.
            </summary>
    <returns>True, wenn die Datei überschrieben werden soll. andernfalls "false".</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>