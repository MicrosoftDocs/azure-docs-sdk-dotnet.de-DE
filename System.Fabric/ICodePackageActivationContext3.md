<Type Name="ICodePackageActivationContext3" FullName="System.Fabric.ICodePackageActivationContext3">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext3 : IDisposable, System.Fabric.ICodePackageActivationContext2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext3 implements class System.Fabric.ICodePackageActivationContext, class System.Fabric.ICodePackageActivationContext2, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext3" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext3&#xA;Implements ICodePackageActivationContext2, IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext3 = interface&#xA;    interface ICodePackageActivationContext2&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext2</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt Aktivierungskontext für die Fabric-Dienst aktiviert Service.
            </summary>
    <remarks>Enthält Informationen über das Dienstmanifest sowie Informationen zu dem Paket derzeit aktivierten Code Geschäfts-Directory, die Kontext-Id usw.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext3.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetDirectory : string -&gt; string" Usage="iCodePackageActivationContext3.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            Ruft den Pfad zum Unterverzeichnis im Arbeitsverzeichnis mit dem Namen "LogicalDirectoryName" ab.
            </summary>
        <returns>Der Pfad zum Unterverzeichnis mit dem Namen LogicalDirectoryName im Arbeitsverzeichnis</returns>
        <remarks>Löst eine Ausnahme aus, wenn LogicalDirectoryName Arbeit im Verzeichnis nicht gefunden wird.
            Andernfalls wird der Verzeichnispfad WorkDirectory\logicalDirectoryName zurückgegeben, die einen symbolischen Link mit mit Namen unter LogicalDirectories Abschnitt ClusterManifest angegebene Verzeichnis ist.
            zum Beispiel: Wenn Sie angegeben haben <LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" /> und der Aufruf dieser Methode mit DirectoryName "Foo" wird zurückgegeben, Pfad WorkDirectory\Foo. Versucht, Schreibvorgänge zurückgegeben, dass der Pfad zum D:\Foo\NodeId\ApplicationType_ApplicationVersion geleitet werden.
            Diese Methode ist Groß-/Kleinschreibung beachtet, daher selbst wenn Sie DirectoryName Foo sagen Sie es noch Sie Verzeichnispfad WorkDirectory\Foo zurück.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>