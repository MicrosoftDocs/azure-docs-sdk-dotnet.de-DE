<Type Name="PartitionSelector" FullName="System.Fabric.PartitionSelector">
  <TypeSignature Language="C#" Value="public class PartitionSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit PartitionSelector extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionSelector" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionSelector" />
  <TypeSignature Language="F#" Value="type PartitionSelector = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist eine Hilfsklasse für Partitionen auswählen. 
            </summary>
    <remarks>
            Sie können den Benutzer zur Auswahl von Partitionen an, für die Prüfbarkeit APIs konfiguriert werden. Die Auswahl kann eine bestimmte Partition eines Diensts auf Grundlage der Id oder Schlüssel oder eine zufällige Partition eines Diensts sein.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="partitionSelector.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">PartitionSelector, t.o verglichen werden soll.</param>
        <summary>
            Vergleicht, ob zwei PartitionSelectors identisch sind.
            </summary>
        <returns>"true", wenn "false" ist dies nicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="partitionSelector.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Basis GetHashCode()
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionIdOf (Uri serviceName, Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionIdOf(class System.Uri serviceName, valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionIdOf(System.Uri,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionIdOf (serviceName As Uri, partitionId As Guid) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionIdOf : Uri * Guid -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionIdOf (serviceName, partitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, deren Partition muss ausgewählt werden.</param>
        <param name="partitionId">Die PartitionId für die Partition.</param>
        <summary>
            Wählt eine Partition für den Dienst, der die PartitionId angegeben.
            </summary>
        <returns>Erstellt von PartitionSelector.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionKeyOf (Uri serviceName, long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionKeyOf(class System.Uri serviceName, int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionKeyOf(System.Uri,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionKeyOf (serviceName As Uri, partitionKey As Long) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionKeyOf : Uri * int64 -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionKeyOf (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, deren Partition muss ausgewählt werden.</param>
        <param name="partitionKey">Der Partitionsschlüssel der angehört. die Partition ausgewählt werden.</param>
        <summary>
            Wählt eine Partition für den Dienst, den der angegebenen Partitionsschlüssel angehört.
            </summary>
        <returns>Erstellt von PartitionSelector.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector PartitionKeyOf (Uri serviceName, string partitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector PartitionKeyOf(class System.Uri serviceName, string partitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.PartitionKeyOf(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PartitionKeyOf (serviceName As Uri, partitionName As String) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member PartitionKeyOf : Uri * string -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.PartitionKeyOf (serviceName, partitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, deren Partition muss ausgewählt werden.</param>
        <param name="partitionName">Der Name der Partition, die muss ausgewählt werden.</param>
        <summary>
            Wählt eine Partition für den Dienst mit den angegebenen PartitionName an.
            </summary>
        <returns>Erstellt von PartitionSelector.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RandomOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector RandomOf (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector RandomOf(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.RandomOf(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RandomOf (serviceName As Uri) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member RandomOf : Uri -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.RandomOf serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, deren Partition muss ausgewählt werden.</param>
        <summary>
            Wählt eine zufällige Partition aus, für den angegebenen Dienst.
            </summary>
        <returns>Erstellt von PartitionSelector.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SingletonOf">
      <MemberSignature Language="C#" Value="public static System.Fabric.PartitionSelector SingletonOf (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.PartitionSelector SingletonOf(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.SingletonOf(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SingletonOf (serviceName As Uri) As PartitionSelector" />
      <MemberSignature Language="F#" Value="static member SingletonOf : Uri -&gt; System.Fabric.PartitionSelector" Usage="System.Fabric.PartitionSelector.SingletonOf serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, deren Partition muss ausgewählt werden.</param>
        <summary>
            Wählt die Singleton-Partition für einen Dienst an.
            </summary>
        <returns>Erstellt von PartitionSelector.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionSelector.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionSelector.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Die Zeichenfolgendarstellung der Partition Selektor.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der Selektor.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>